---
title: Field Of Opposition
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - illusion
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #162: Ruins of the Radiant Siege
aliases: "Actor.zf4ZZnniH0k16rOu" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Field Of Opposition"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[illusion]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 35
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +33, __Ref__ +30, "
hp: 150
health:
  - name: ""
  - name: "HP"
    desc: "150; __Hardness__ 20; __Immunities__  object immunities; __Weaknesses__ sonic 20"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: " +35"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A distortion in space spawns an aggressive, malevolent shadow duplicate of any characters who pass between Terimor's faces."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Thievery check (legendary) to permanently disable the planar distortion (DC increases by 2 for each duplicate still extant), or [[Spells/Dispel Magic|Dispel Magic]] (10th level; counteract DC 42) to destroy the planar distortion"
attacks:
  - name: ""

  - name: "Spawn Mirror Duplicate"
    desc: "`pf2:r` (divine, teleportation) **Trigger** A creature moves between the two glass faces of Olansa Terimor\n* * *\n\n**Effect** The planar rift disgorges an evil mirror duplicate of the creature, and the duplicate rolls initiative.\n\nThe field of opposition can use this reaction once per round but can't spawn a duplicate of a creature that already has a mirror duplicate in existence."

  - name: "Mirror Duplicate"
    desc: "passive A mirror duplicate rolls initiative with a +45 modifier. It uses the same statistics as the original creature, but with a +2 status bonus to AC, attacks, and saving throws. The duplicate is evil, and any abilities reliant on alignment change accordingly. The duplicate is also aggressive, attacking and taking other hostile actions available to it against anyone other than mirror duplicates.\n\nIt has three actions and one reaction and can use any of the original creature's abilities. Any limited-use abilities (such as spell slots) are based on what the original had when duplicated and are used up separately from the original creature's. The duplicate also has duplicates of the creature's worn and held items, but not consumables.\n\nA duplicate is destroyed when reduced to 0 HP, when the trap is disabled or destroyed, or when the duplicate leaves area E2. Its duplicated items disappear when they leave its grip, though they last long enough for ranged Strikes."



```

```encounter-table
name: Field Of Opposition
creatures:
  - 1: Field Of Opposition
```

