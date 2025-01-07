---
title: Spike Launcher
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #163: Ruins of Gauntlight
aliases: "Actor.G2BKonD9XZL7Ntap" 
level: 0
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Spike Launcher"
level: "Hazard 0"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 9
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +3, "
hp: 16
health:
  - name: ""
  - name: "HP"
    desc: "16; __Hardness__ 3; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: " +9"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A jagged spike of metal shoots from a hidden launcher."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 16 Thievery check to disable one of the four launchers or DC 12 Acrobatics check to step over a trip line (this doesn't disarm the trap, but avoids triggering it)"
attacks:
  - name: ""
  - name: "Melee"
    desc: "Spike +11 (range 20 feet) "

  - name: "Spike"
    desc: "`pf2:r` **Trigger** A creature crosses one of the trip lines\n* * *\n\n**Effect** A spike launches along the trip line's path against the triggering creature, making a ranged Strike."



```

```encounter-table
name: Spike Launcher
creatures:
  - 1: Spike Launcher
```

