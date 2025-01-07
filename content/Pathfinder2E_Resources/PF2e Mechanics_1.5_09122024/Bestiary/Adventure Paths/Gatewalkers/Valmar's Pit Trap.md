---
title: Valmar's Pit Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #188: They Watched the Stars
aliases: "Actor.0VbU6Lmuoe2OjZAQ" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #188: They Watched the Stars"
name: "Valmar's Pit Trap"
level: "Hazard 4"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #188: They Watched the Stars_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +2, __Ref__ +3, "
hp: 6
health:
  - name: ""
  - name: "HP"
    desc: "6; __Hardness__ 1; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The ground here is made of loosely packed soil that, when stepped upon, collapses."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Survival check (trained) to reinforce the dirt so it's safe to walk on, or DC 18 Thievery check (trained) to collapse the trap from a safe distance"
attacks:
  - name: ""

  - name: "Collapse"
    desc: "`pf2:r` **Trigger** A creature steps onto any space in the dotted area on the map, or at least 30 pounds of pressure is put on the area\n* * *\n\n**Effect** The ground gives way. The triggering creature falls 20 feet down the hole, taking 10 bludgeoning and landing [[Conditions/Prone|Prone]] in area **E10**. A creature can [[Actions/Grab an Edge|Grab an Edge]] to avoid falling."


  - name: "Reset"
    desc: "Creatures can still fall into the pit, but the soil must be replaced for the trap to become hidden again."
```

```encounter-table
name: Valmar's Pit Trap
creatures:
  - 1: Valmar's Pit Trap
```

