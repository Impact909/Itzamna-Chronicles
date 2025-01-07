---
title: Mist Projector Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - cold
  - trap
  - water
  - pf2eHazard

source: Pathfinder #194: Cult of the Cave Worm
aliases: "Actor.ra26QmffHOtBa6Th" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Mist Projector Trap"
level: "Hazard 7"


trait_01: [[cold]]
trait_02: [[trap]]
trait_03: [[water]]
modifier: 13
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +10, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60,  (BT 30); __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Hidden jets expel gas that quickly freezes, causing limited damage to nearby books."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Thievery check (expert) to deactivate the trap without its control key or DC 26 Crafting check to create and apply a chemical that neutralizes the gas."
attacks:
  - name: ""

  - name: "Icy Mist"
    desc: "action (cold, water) **Trigger** The northeast bookshelf is touched\n* * *\n\n**Effect** Freezing mist fills a 30-foot cone originating from the room's northeast corner. Creatures in the area take 5d8 cold damage (DC 25 Fortitude check). Creatures who fail or critically fail the saving throw take 2d8 persistent cold damage for up to 3 rounds. The affected area is filled with mist that functions as obscuring mist for 3 rounds."


  - name: "Reset"
    desc: "8 hours"
```

```encounter-table
name: Mist Projector Trap
creatures:
  - 1: Mist Projector Trap
```

