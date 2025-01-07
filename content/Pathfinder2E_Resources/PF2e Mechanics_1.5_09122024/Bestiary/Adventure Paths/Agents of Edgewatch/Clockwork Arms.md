---
title: Clockwork Arms
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #161: Belly of the Black Whale
aliases: "Actor.ISZGxQ20bylvlbTc" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Clockwork Arms"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[mechanical]]
modifier: 30
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +23, __Ref__ +26, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, to destroy one arm; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four claw-tipped clockwork arms suspended from the ceiling pick up and deposit creatures into a nearby hatch."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to jam and deactivate one of the arms or DC 46 Athletics check (legendary) to tear an arm off the machine."
attacks:
  - name: ""

  - name: "Arm Activation"
    desc: "`pf2:r` **Trigger** The Rumormonger or the Inkmaster enters the room\n* * *\n\n**Effect** The trap rolls initiative."
  - name: "Melee"
    desc: "Claw +28 () "

  - name: "Open Hatch"
    desc: "action The metal hatch opens and the arms deposit a grabbed Medium or smaller creature into the hole. The creature becomes caught in the gears (see Caught in Gears) for 1 round before emerging in area **K5**. **Reset** Rewinding the gears for 1d4 minutes resets the trap."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action per arm destroyed or disabled. On its turn, the trap makes claw Strikes against creatures other than the Rumormonger or the Inkmaster. If an arm already has a creature grabbed, the trap spends 2 actions to use its Open Hatch ability."

```

```encounter-table
name: Clockwork Arms
creatures:
  - 1: Clockwork Arms
```

