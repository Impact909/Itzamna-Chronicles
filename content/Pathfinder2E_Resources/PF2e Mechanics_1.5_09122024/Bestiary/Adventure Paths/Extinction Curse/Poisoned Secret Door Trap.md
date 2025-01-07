---
title: Poisoned Secret Door Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #154: Siege of the Dinosaurs
aliases: "Actor.hEBtS6ReDhxTPIzK" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Poisoned Secret Door Trap"
level: "Hazard 14"


trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 24
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +19, "
hp: 92
health:
  - name: ""
  - name: "HP"
    desc: "92; __Hardness__ 23; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 34" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Multiple tiny needles filled with poison are embedded in this secret door, spring-loaded to pop out."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 34 Thievery check (expert) to break the mechanism, or DC 39 Perception check (master) to identify the three stones that, when pressed, prevent the trap from triggering"
attacks:
  - name: ""
  - name: "Melee"
    desc: "Needles +32 () "

  - name: "Spring"
    desc: "`pf2:r` (attack) **Trigger** A creature tries to open the door, whether or not it is still locked, without first depressing three specific stones on the door's surface\n* * *\n\n**Effect** Needles pop out of the door at the triggering creature."

  - name: "Purple Worm Venom"
    desc: "passive (poison) **Saving Throw** DC 34 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 5d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 2** 6d6 poison damage and enfeebled 2 (1 round)\n\n**Stage 3** 8d6 poison damage and enfeebled 2 (1 round)."


  - name: "Reset"
    desc: "If disabled, the trap resets after 1 minute."
```

```encounter-table
name: Poisoned Secret Door Trap
creatures:
  - 1: Poisoned Secret Door Trap
```

