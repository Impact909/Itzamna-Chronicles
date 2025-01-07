---
title: "Burning Mammoth Reaver"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qV2IRUjXoBfbHxbq" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Burning Mammoth Reaver"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #175: Broken Tusk Moon"
name: "Burning Mammoth Reaver"
level: "Creature 2"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Hallit"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +7, Nature: +8, Survival: +8"
abilityMods: [4, 2, 1, 0, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder #175: Broken Tusk Moon_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +8, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|Battle Axe]], 3x [[Equipment/Javelin|Javelin]], 2x [[Equipment/Tallow Bomb (Lesser)|Tallow Bomb (Lesser)]], [[Equipment/Chain Shirt|Chain Shirt]]"
  - name: "Reaver's Howl"
    desc: "  When the reaver attempts an Intimidation check to [[Actions/Demoralize|Demoralize]], the reaver compares the result of the Intimidation check to the Will DC of each non-Burning Mammoth creature within 30 feet, determining the effect separately for each creature. The reaver's howl ignores the usual circumstance penalty to the Intimidation check for not speaking the same language as the target."

abilities_mid:
  - name: ""
  - name: "Spurred by Death"
    desc: "`pf2:r`  **Trigger** An ally within 30 feet reduces a creature to 0 HP\n* * *\n\n**Effect** The reaver Steps or Strides."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+11 (sweep)\n__Damage__  1d8 + 4 slashing plus cut-down"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+9 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Tallow Bomb"
    desc: "+9 (splash, thrown 20 ft.)\n__Damage__  1d4 fire 1 fire"

  - name: "Cut Down"
    desc: "  When a reaver hits a creature with a battle axe Strike, the target must succeed at a DC 16 Fortitude check save or fall [[Conditions/Prone|Prone]]. If the creature critically fails its save, it takes 1d6 bludgeoning damage as it falls prone."
 
```

```encounter-table
name: Burning Mammoth Reaver
creatures:
  - 1: Burning Mammoth Reaver
```




