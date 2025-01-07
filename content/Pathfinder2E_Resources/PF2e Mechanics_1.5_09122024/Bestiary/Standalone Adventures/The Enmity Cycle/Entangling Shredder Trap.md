---
title: Entangling Shredder Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: The Enmity Cycle
aliases: "Actor.UXYJzp7aNkvpHrIU" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Enmity Cycle"
name: "Entangling Shredder Trap"
level: "Hazard 6"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder Adventure: The Enmity Cycle_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +16, "
hp: 54
health:
  - name: ""
  - name: "HP"
    desc: "54, to cut the barbed ropes and disable the trap; __Hardness__ 13; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(expert) to notice the pressure plates under the rugs"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Dozens of ropes embedded with steel barbs spring out from the walls when at least two creatures step on the rugs."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 24 Thievery check (expert) on the pressure plates."
attacks:
  - name: ""

  - name: "Entangling Ropes"
    desc: "`pf2:r` (attack) **Trigger** Two creatures enter the hallway or end their turn in the hallway\n* * *\n\n**Effect** The trap makes a barbed rope Strike against the triggering creatures. This trap doesn't take a multiple attack penalty."
  - name: "Melee"
    desc: "Barbed Rope +20 () "

  - name: "Grasping Ropes"
    desc: "passive The ropes whip around the limbs of the target. The target must attempt a DC 25 Reflex check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Off-Guard|Off-Guard]] until it cuts the ropes or [[Actions/Escape|Escapes]] (DC 25).\n\n**Critical Failure** As failure, but the target is also [[Conditions/Immobilized|Immobilized]]."

  - name: "No MAP"
    desc: "passive This trap doesn't take a multiple attack penalty."


  - name: "Reset"
    desc: ""
```

```encounter-table
name: Entangling Shredder Trap
creatures:
  - 1: Entangling Shredder Trap
```

