---
title: Poisonous Atmosphere
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - magical
  - mental
  - poison
  - pf2eHazard
  - complex
source: Pathfinder #187: The Seventh Arch
aliases: "Actor.slmb8zYLrhgqniXk" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Poisonous Atmosphere"
level: "Hazard 1"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[magical]]
trait_03: [[mental]]
trait_04: [[poison]]
modifier: 5
sourcebook: "_Pathfinder #187: The Seventh Arch_"
perception:
  - name: ""
  - name: "Stealth DC 5" 
    desc: "(expert) to identify the source of sudden nausea"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Aucturn's poisonous, magical atmosphere has strange effects on the planet's creatures."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Survival check (trained) or Occultism (trained) to breathe pockets of safe air trapped in bags and clothing"
attacks:
  - name: ""

  - name: "Poisonous Atmosphere"
    desc: "`pf2:r` (illusion, mental, occult) **Trigger** A non-native creature breathes the atmosphere\n* * *\n\n**Effect** The triggering creature must attempt a DC 17 Fortitude check save. The hazard then rolls initiative.\n* * *\n\n**Critical Success** The creature is invigorated by the atmosphere and is [[Conditions/Quickened|Quickened]] for 1 round.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Clumsy|Clumsy 1]].\n\n**Critical Failure** The creature is [[Conditions/Confused|Confused]] for 1 round."

  - name: "Routine"
    desc: "(1 action; illusion, mental, occult) The atmosphere continues to affect all creatures in the area, requiring a new Fortitude save each round against its Poisonous Atmosphere. A creature holding its breath gains a +2 circumstance bonus to the save."

```

```encounter-table
name: Poisonous Atmosphere
creatures:
  - 1: Poisonous Atmosphere
```

