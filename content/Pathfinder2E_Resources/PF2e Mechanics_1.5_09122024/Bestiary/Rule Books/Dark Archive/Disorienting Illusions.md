---
title: Disorienting Illusions
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - illusion
  - magical
  - trap
  - visual
  - pf2eHazard

source: Pathfinder Dark Archive
aliases: "Actor.qlElByHIYDWtEXGa" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Disorienting Illusions"
level: "Hazard 1"


trait_01: [[illusion]]
trait_02: [[magical]]
trait_03: [[trap]]
trait_04: [[visual]]
modifier: 10
sourcebook: "_Pathfinder Dark Archive_"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: " +10"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Illusions cloaking this chamber cause it to appear distorted and constantly shifting, with the room and all its contents appearing tilted, irregular, and in motion."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 17 Crafting check (trained) to calculate the room's dimensions despite the illusions, or [[Spells/Dispel Magic|Dispel Magic]] (1st level; counteract DC 17) to counteract the illusions"
attacks:
  - name: ""

  - name: "Disorient"
    desc: "`pf2:r` (arcane, illusion, mental, visual) **Trigger** A creature enters the room\n* * *\n\n**Effect** Illusions cause the appearance of the room and the objects inside it to constantly warp, shift, bend, and distort for 1 minute. Each creature in the room while it's distorting must attempt a DC 17 Perception check check.\n* * *\n\n**Critical Success** The creature disbelieves the illusions and is unaffected.\n\n**Success** The creature disbelieves the illusions but still sees them. It treats the room as difficult terrain.\n\n**Failure** The creature is fooled by the illusions. It treats the room as difficult terrain and becomes [[Conditions/Sickened|Sickened 1]]. As long as it remains in the room, it can't reduce its sickened value below 1.\n\n**Critical Failure** As failure, but each time the creature Archive attempts a move action, it must succeed at a DC 5 Flat check or they lose the action, and on a critical failure, it also falls [[Conditions/Prone|Prone]]."


  - name: "Reset"
    desc: "1 minute"
```

```encounter-table
name: Disorienting Illusions
creatures:
  - 1: Disorienting Illusions
```

