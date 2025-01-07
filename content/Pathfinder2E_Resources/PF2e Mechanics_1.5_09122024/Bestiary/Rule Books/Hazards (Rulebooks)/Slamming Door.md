---
title: Slamming Door
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.tid5HknSYMIhlIyy" 
level: 1
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Slamming Door"
level: "Hazard 1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder GM Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +2, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20; __Hardness__ 5; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Pressure-sensitive panels in the floor connect to a stone slab hidden in a hallway's ceiling."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 15 Thievery check (trained) on the floor panels before the slab falls"
attacks:
  - name: ""

  - name: "Slam Shut"
    desc: "`pf2:r` **Trigger** Pressure is placed on any floor tile.\n* * *\n\n**Effect** The door falls, closing off the hallway. The stone slab deals 3d8 bludgeoning damage to anyone beneath or adjacent to the slab when it drops and pushes them out of its space in a random direction. A creature that succeeds at a DC 17 Reflex check save takes no damage and rolls out of the way in a random direction. On a critical success, they can choose the direction.\n\nLifting the fallen slab requires a successful DC 25 Athletics check check.\n\nHitting the floor panels triggers the trap. The slab uses the same AC and saves as the trap, but it has Hardness 12, HP 48 (BT 24)."



```

```encounter-table
name: Slamming Door
creatures:
  - 1: Slamming Door
```

