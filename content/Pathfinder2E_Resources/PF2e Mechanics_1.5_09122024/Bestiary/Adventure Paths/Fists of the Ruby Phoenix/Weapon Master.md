---
title: "Weapon Master"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y6LGi61fH4XmOirE" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Weapon Master"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Weapon Master"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; "
languages: "Taldane, Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +23, Intimidation: +22, Survival: +24, Warfare Lore: +23"
abilityMods: [5, 2, 4, 2, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +22, __Will__ +24"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Katana|+2 Greater Striking Katana]], [[Equipment/Sling|+1 Striking Sling]], [[Equipment/Studded Leather Armor|+1 Resilient Studded Leather Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Katana"
    desc: "+28 (deadly d8, magical, two-hand d10, versatile p)\n__Damage__  3d6 + 11 slashing"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+22 (magical, propulsive, range increment 50 feet, reload 1)\n__Damage__  2d6 + 11 bludgeoning"

  - name: "Dueling Expertise"
    desc: "  The weapon master deals an extra 2d10 damage to creatures that are not adjacent to any allies or other foes."

  - name: "Swift Blow"
    desc: "`pf2:2` (flourish) **Requirements** The weapon master is not wielding a weapon.\n* * *\n\n**Effect** The weapon master Interacts to draw a melee weapon without triggering reactions and makes a Strike with that weapon. The target is [[Conditions/Off-Guard|Off-Guard]] against this Strike. The weapon master deals an extra 2d8 bleed with the Strike."
 
```

```encounter-table
name: Weapon Master
creatures:
  - 1: Weapon Master
```




