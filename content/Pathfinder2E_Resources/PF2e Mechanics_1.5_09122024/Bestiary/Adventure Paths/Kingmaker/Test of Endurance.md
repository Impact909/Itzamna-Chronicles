---
title: Test of Endurance
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - cold
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.OfulrhIeqnvnFFe5" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Test of Endurance"
level: "Hazard 13"


trait_01: [[cold]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 30
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC 40" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The room fills with swirling vortexes of freezing wind that swiftly freeze flesh and chill the bones."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) to adjust the wheel's mechanisms so that it won't trigger the Test of Endurance, or [[Spells/Dispel Magic|Dispel Magic]] (7th level, counteract DC 31) to counteract the trap's magic."
attacks:
  - name: ""

  - name: "Freezing Wind"
    desc: "`pf2:r` (cold) **Trigger** A creature critically fails at an attempt to Rotate the Wheel or releases their grip on the wheel once they've started to rotate it\n\n**Effect** A vortex of freezing wind howls through the room-all creatures in the room must attempt a DC 33 Fortitude check save.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes 1d6 cold damage for each revolution the wheel has been rotated (max 7d6).\n\n**Failure** The creature takes 2d6 cold damage for each revolution the wheel has been rotated (max 14d6) and becomes [[Conditions/Fatigued|Fatigued]].\n\n**Critical Failure** The creature takes 3d6 cold damage for each revolution the wheel has been rotated (max 21d6), becomes [[Conditions/Drained|Drained 1]], and becomes fatigued."


  - name: "Reset"
    desc: "The trap resets automatically."
```

```encounter-table
name: Test of Endurance
creatures:
  - 1: Test of Endurance
```

