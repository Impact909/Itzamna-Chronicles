---
title: Stygian Fires
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - cold
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.sB4aAHMeuII5GiU5" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Stygian Fires"
level: "Hazard 12"


trait_01: [[cold]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 25
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Freezing black fire bursts from the two quartz altars, filling the room with numbing black flames that scour away memories and emotions as swiftly as they sear flesh and bone."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Thievery check (master) to sever the links between the door and the lanterns, DC 35 Religion check (master) to use prayer to deactivate the divine magic, or [[Spells/Dispel Magic|Dispel Magic]] (6th level; counteract DC 30) to counteract the trap"
attacks:
  - name: ""

  - name: "Stygian Fire"
    desc: "`pf2:r` (cold, divine) **Trigger** The doors to area **E3** are opened without someone making blood offerings and lighting the lanterns.\n* * *\n\n**Effect** Every creature in area **E2** must attempt a DC 32 Reflex check save.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes 3d10+13 cold damage and is [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\n**Failure** The creature takes 6d10+27 cold damage and is stupefied 1.\n\n**Critical Failure** The creature takes 6d10+27 cold damage, takes 1d10 persistent cold damage, and is [[Conditions/Stupefied|Stupefied 2]]."


  - name: "Reset"
    desc: "The trap resets one minute after the doors to area **E3** are closed."
```

```encounter-table
name: Stygian Fires
creatures:
  - 1: Stygian Fires
```

