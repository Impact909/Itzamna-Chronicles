---
title: Poisoned Dart Statue
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #160: Assault on Hunting Lodge Seven
aliases: "Actor.36HH0Dg5J1q827Uz" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Poisoned Dart Statue"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[mechanical]]
modifier: 24
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +20, __Ref__ +25, "
hp: 96
health:
  - name: ""
  - name: "HP"
    desc: "96; __Hardness__ 24; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 24" 
    desc: "(expert) or DC 39 Perception check (master) to notice the control panel. Anyone specifically searching the name plate of Abresha Tallow-Hands locates the control panel automatically."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Countless poison darts fire from holes in the statues and walls of this hall."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 34 Thievery check (master) on the control panel deactivates the trap."
attacks:
  - name: ""

  - name: "Dart Volley"
    desc: "`pf2:r` **Trigger** A creature makes noise in the hall, which can be avoided with a successful DC 28 Stealth check check\n* * *\n\n**Effect** The trap makes a poisoned dart Strike against the triggering creature, then rolls initiative."
  - name: "Melee"
    desc: "Poisoned Dart +28 () "

  - name: "Continuous Barrage"
    desc: "`pf2:0` **Trigger** A creature within the hallway finishes an action while the trap is active\n* * *\n\n**Effect** The trap makes a poisoned dart Strike against the triggering creature."

  - name: "Terinav Root Poison"
    desc: "passive (poison) **Saving Throw** DC 28 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 4d6 poison damage and clumsy 2 (1 round)\n\n**Stage 2** 5d6 poison damage, clumsy 2, and -5-foot status penalty to all Speeds (1 round)\n\n**Stage 3** 7d6 poison damage, clumsy 2, and -10-foot status penalty to all Speeds (1 round)"

  - name: "Routine"
    desc: "(1 action) The trap launches one dart against every creature in the hall as 1 action. Because it launches darts continuously, the trap can also use the Continuous Barrage free action (see below) to launch darts at each creature during that creature's turn. The trap doesn't take a multiple attack penalty."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 minute."
```

```encounter-table
name: Poisoned Dart Statue
creatures:
  - 1: Poisoned Dart Statue
```

