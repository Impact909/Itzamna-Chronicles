---
title: Caustic Vapor
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #149: Against the Scarlet Triad
aliases: "Actor.btqd1TpPRxKL0cpb" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Caustic Vapor"
level: "Hazard 17"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 30
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
perception:
  - name: ""
  - name: "Stealth DC 40" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The door slams shut, and poison gas fills the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 36 Occultism check (master) or DC 36 Religion check (master) to exorcise the spirits"
attacks:
  - name: ""

  - name: "Breath Snatcher"
    desc: "`pf2:r` (occult) **Trigger** A living creature other than an ooze spends at least 3 rounds in the room\n* * *\n\n**Effect** The trap activates and fills the area with caustic nightmare vapor, exposing all creatures within."

  - name: "Caustic Nightmare Vapor"
    desc: "passive (acid, poison) Oozes are immune to this poison\n\n**Saving Throw** DC 38 Fortitude check\n\n**Onset** 1 round\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 4d6 acid damage and [[Conditions/Confused|Confused]] (1 round)\n\n**Stage 2** 6d6 acid damage, confused, and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** 8d6 acid damage, confused, off-guard, and [[Conditions/Stupefied|Stupefied 2]] (1 round)"


  - name: "Reset"
    desc: "The trap resets after 1 day."
```

```encounter-table
name: Caustic Vapor
creatures:
  - 1: Caustic Vapor
```

