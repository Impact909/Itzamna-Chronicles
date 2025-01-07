---
title: Caustic Gas Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - acid
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #195: Heavy is the Crown
aliases: "Actor.b9RhtTVxoQ1TRwvG" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Caustic Gas Trap"
level: "Hazard 9"


trait_01: [[acid]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 20
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Pressure plates in the hall trigger the release of caustic gas."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Crafting check (master) to neutralize the acid or DC 30 Thievery check (master) to disable the pressure plates"
attacks:
  - name: ""

  - name: "Collapse"
    desc: "`pf2:r` **Trigger** A creature in contact with the ground travels down this hall\n* * *\n\n**Effect** Caustic gas fills the hall, dealing 4d10+26 acid damage to all creatures in area **D5** (DC 32 Reflex check save)."


  - name: "Reset"
    desc: "A 10-minute Interact activity and a new supply of caustic gas."
```

```encounter-table
name: Caustic Gas Trap
creatures:
  - 1: Caustic Gas Trap
```

