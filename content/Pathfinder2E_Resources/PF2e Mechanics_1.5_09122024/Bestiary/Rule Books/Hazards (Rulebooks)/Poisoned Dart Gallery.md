---
title: Poisoned Dart Gallery
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.0NLslR4cWwj5W8uQ" 
level: 8
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Poisoned Dart Gallery"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 16
sourcebook: "_Pathfinder GM Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +13, __Ref__ +17, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56, to destroy the control panel and disable the trap; __Hardness__ 14; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 16" 
    desc: "(expert) or DC 31 Perception check (master) to notice the control panel"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Countless holes to launch poison darts from line a long hallway with a hidden control panel on the far end."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 21 Thievery check (expert) on the control panel deactivates the trap."
attacks:
  - name: ""

  - name: "Dart Volley"
    desc: "`pf2:r` (attack) **Trigger** A creature enters the hallway or ends its turn in the hallway\n* * *\n\n**Effect** The trap makes a poisoned dart Strike against the triggering creature, then rolls initiative."
  - name: "Melee"
    desc: "Poisoned Dart +21 () "

  - name: "Continuous Barrage"
    desc: "`pf2:0` **Trigger** A creature within the active gallery finishes an action\n* * *\n\n**Effect** The trap makes a poisoned dart Strike against the triggering creature."

  - name: "Flesset Poison"
    desc: "passive (poison) **Saving Throw** DC 22 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 2d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 3d6 poison damage and [[Conditions/Clumsy|Clumsy 3]] (1 round)"

  - name: "No MAP"
    desc: "passive The poisoned dart Strikes do not apply a MAP."

  - name: "Routine"
    desc: "(1 action) The trap launches one dart against every creature in the gallery as 1 action. Because it launches darts continuously, the trap can also use the Continuous Barrage free action (see below) to launch darts at each creature during that creature's turn."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 minute."
```

```encounter-table
name: Poisoned Dart Gallery
creatures:
  - 1: Poisoned Dart Gallery
```

