---
title: Boiling Fountains
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.ufPRNEdGAoGM2p7i" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Boiling Fountains"
level: "Hazard 2"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 8; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained) to spot the pressure plates"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four pressure plates beneath the floorboards activate dragon-headed fountains on either side of the room, which spray boiling water across the area between them."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 21 Thievery check (trained) to disable each pressure plate, DC 16 Thievery check to jam each fountain, or DC 18 Thievery check to deflect a fountain's spray"
attacks:
  - name: ""

  - name: "Scalding Spray"
    desc: "`pf2:r` (fire, water) **Trigger** Weight is placed on one of the squares marked with \"T\" on the map, triggering a pressure plate\n* * *\n\n**Effect** The fountains spray boiling water across their own squares and the 10-foot-by-20-foot area between them (marked with dotted lines), dealing 4d6+4 fire damage to any creatures in the area (DC 22 Reflex check save)."


  - name: "Reset"
    desc: "Once a pressure plate has been activated, it must be reset manually."
```

```encounter-table
name: Boiling Fountains
creatures:
  - 1: Boiling Fountains
```

