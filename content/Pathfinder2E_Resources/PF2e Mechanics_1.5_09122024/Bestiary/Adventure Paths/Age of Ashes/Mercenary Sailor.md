---
title: "Mercenary Sailor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0ywewzFHMY9oi5eM" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Mercenary Sailor"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Mercenary Sailor"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +13, Survival: +11, Thievery: +11, Sailing Lore: +13"
abilityMods: [4, 4, 3, 0, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +12, __Ref__ +15, __Will__ +9"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|Scimitar]], [[Equipment/Shortbow|Shortbow]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Shipboard Grace"
    desc: "  The mercenary sailor is not [[Conditions/Off-Guard|Off-Guard]] while [[Actions/Balance|Balancing]] or [[Actions/Climb|Climbing]] while on a watercraft."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+15 (forceful, sweep)\n__Damage__  1d6 + 7 slashing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+15 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 3 piercing"

  - name: "Mobility"
    desc: "  When the sailor takes a Stride action to move half their Speed or less, that movement does not trigger reactions."

  - name: "Shipboard Savvy"
    desc: "  The sailor's melee Strikes deal 2d6 extra precision damage if both the sailor and the target are on watercraft."
 
```

```encounter-table
name: Mercenary Sailor
creatures:
  - 1: Mercenary Sailor
```




