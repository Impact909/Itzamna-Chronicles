---
title: "Bystander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a6ONqgTlKfy4mWM3" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Bystander"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Bystander"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Medicine: +9, Stealth: +7"
abilityMods: [4, 2, 2, 0, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +9, __Ref__ +7, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|Staff]], [[Equipment/Sling|Sling]], [[Equipment/Hide Armor|Hide Armor]], 20x [[Equipment/Sling Bullets|Sling Bullets]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+9 (monk, two-hand d8)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+7 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "Primal Prepared Spells"
    desc: "DC 16, attack +8; __1st __  _[[Spells/Heal|Heal]]_, _[[Spells/Runic Weapon|Runic Weapon]]_\n__Cantrips__  __(1st)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"
 
```

```encounter-table
name: Bystander
creatures:
  - 1: Bystander
```


Variant elite guard

Guards are rank-and-file members of a town watch or city guard, trained to look for trouble, take down criminals, and follow orders. They are a match for only the most fledgling of adventurers and criminals, but, given time, the settlement can usually muster them in numbers sufficient to neutralize most threats.

* * *

Larger societies rely on those with the authority and the ability to interpret and enforce laws. In good-aligned societies, these officials carry out their duties fairly. In neutral and evil ones, these officials can be harsh and cruel (with an altered alignment to reflect this), imposing severe punishments on those who can't pay for mercy.
