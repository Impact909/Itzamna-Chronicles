---
title: Test of Strength
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.4XkrKlrZSsSWsJa2" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Test of Strength"
level: "Hazard 13"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 27
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC 37" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The steps angle downward into a slope, releasing all currently placed boulders to roll back down to the north."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 37 Thievery check (expert) to disable the [[Conditions/Hidden|Hidden]] hinges for one of the steps, thereby locking all four steps into place"
attacks:
  - name: ""

  - name: "Open Doors"
    desc: "`pf2:r` **Trigger** All four boulders are placed within six minutes;\n\n**Effect** the doors to area **D4** open."

  - name: "Release Boulders"
    desc: "`pf2:r` **Trigger** All four boulders are not placed within six minutes\n\n**Effect** All four steps angle downward, causing any boulders held within to roll toward area **D1**. Each rolling boulder inflicts 3d6 + 6 bludgeoning damage on all creatures in area **D2**(DC 37 Reflex check)."


  - name: "Reset"
    desc: "The trap Releases Boulders 24 hours after it Opens Doors. Once the trap Releases Boulders, it resets itself automatically."
```

```encounter-table
name: Test of Strength
creatures:
  - 1: Test of Strength
```

