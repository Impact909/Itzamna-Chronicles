---
title: Slamming Gate
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder #208: Hoof, Cinder, and Storm
aliases: "Actor.gfz0jQMkRRHuUXM6" 
level: 5
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Slamming Gate"
level: "Hazard 5"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +5, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A pressure-sensitive floor panel causes a spiked door to slam down into place from the ceiling, skewering anyone caught underneath."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (trained) to jam either the floor panel or the associated winch"
attacks:
  - name: ""

  - name: "Slam Closed"
    desc: "`pf2:r` **Trigger** Pressure is placed on the associated floor tile\n* * *\n\n**Effect** The door falls, closing off the hallway. The door deals 3d8+3 bludgeoning damage and 3d8+3 piercing damage to anyone beneath or adjacent to the door when it falls, and it pushes them out of its space (away from the door, or in a random direction if the creature is directly beneath the door) as it falls. A creature that succeeds at a DC 22 Reflex check save takes no damage and moves out of the way in a random direction. On a critical success, they choose the direction.\n\nLifting the closed door requires a successful DC 25 Athletics check check. Hitting the floor panels triggers the trap. The slab uses the same AC and saves as the trap, but it has Hardness 8 and 60 HP (BT 30)."



```

```encounter-table
name: Slamming Gate
creatures:
  - 1: Slamming Gate
```

