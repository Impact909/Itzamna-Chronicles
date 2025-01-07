---
title: "Pirate"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5tGrPxp1cWZJjxVJ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Pirate"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Pirate"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Deception: +6, Intimidation: +6, Sailing Lore: +8"
abilityMods: [2, 3, 1, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +8, __Will__ +6"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|Cutlass]], [[Equipment/Dagger|Dagger]], [[Equipment/Padded Armor|Padded Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Bravery"
    desc: "  When the pirate rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cutlass"
    desc: "+10 (forceful, sweep)\n__Damage__  1d6 + 5 slashing"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+11 (agile, versatile s)\n__Damage__  1d4 + 5 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+11 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 5 piercing"

  - name: "Boarding Action"
    desc: "`pf2:2`  The pirate swings on a rope or Strides, moving up to double their Speed. If the pirate boarded or disembarked a boat during this movement, they can make a melee Strike at the end of their movement that deals one extra damage die on a hit."
 
```

```encounter-table
name: Pirate
creatures:
  - 1: Pirate
```



These scourges of the seas are a threat to anyone who spends time away from land.

* * *

Adventurers may need passage on a swift vessel, or they might face danger from raiders at sea or in coastal settlements.
