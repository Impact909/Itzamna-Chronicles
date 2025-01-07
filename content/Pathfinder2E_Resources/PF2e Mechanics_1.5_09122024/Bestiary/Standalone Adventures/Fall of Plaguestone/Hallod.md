---
title: "Hallod"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9B13iAzvZFvUjQ4y" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Hallod"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Hallod"
level: "Creature 3"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +11, Nature: +7, Stealth: +8, Survival: +7"
abilityMods: [4, 3, 1, 0, 2, 0]
speed: 30 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +10, __Will__ +7"
hp: 44
health:
  - name: ""
  - name: HP
    desc: "44"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Kukri|+1 Kukri]], [[Equipment/Leather Armor|Leather Armor]], Key, 10x [[Equipment/Bolts|Bolts]], [[Equipment/Healing Potion (Lesser)|Healing Potion (Lesser)]], 2x [[Equipment/Juggernaut Mutagen (Lesser)|Juggernaut Mutagen (Lesser)]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Kukri"
    desc: "+12 (agile, trip)\n__Damage__  1d6 + 6 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 6 bludgeoning"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+10 (range increment 120 feet, reload 2)\n__Damage__  1d10 + 2 piercing"

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Dirty Trick"
    desc: "  **Trigger** Hallod scores a critical hit with a melee attack.\n* * *\n\n**Effect** Hallod can attempt an Athletics check to [[Actions/Shove|Shove]] or [[Actions/Trip|Trip]] the target of his attack. This uses the same multiple attack penalty as the attack, but it does not count as an additional attack for that penalty"

  - name: "One-Two Move"
    desc: "`pf2:2`  Hallod makes two Strikes, one with each hand; he usually attacks first with his kukri. If this first attack hits, the target is [[Conditions/Off-Guard|Off-Guard]] to the second attack (which for Hallod is usually a fist Strike). The multiple attack penalty applies to these attacks as normal"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  Hallod deals 1d6 extra precision damage precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Hallod
creatures:
  - 1: Hallod
```




