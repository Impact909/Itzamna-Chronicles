---
title: Scroll Shock Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: The Slithering
aliases: "Actor.hvPAzrq1HeMPlhwm" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Scroll Shock Trap"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +21, __Ref__ +15, "
hp: 64
health:
  - name: ""
  - name: "HP"
    desc: "64, See Symbol and Panel Stats; __Hardness__ 16; __Immunities__  object immunities,  critical hits,  precision; __Resistances__ electricity 15"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert) or DC 29 Perception check (expert) to spot the control panel"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Five scroll symbols shoot electricity bolts around the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Thievery check (expert) or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 24)\n\nDC 29 Thievery check (master) to disable the entire trap from the hidden control panel beneath the central slab."
attacks:
  - name: ""

  - name: "Symbol Stats (Each)"
    desc: "passive **Hardness** 16\n\n**HP** 64 (BT 32)\n\n**Resistances** Electricity 15\n\n**Immunities** Critical Hits, Object Immunities, Precision Damage"

  - name: "Control Panel Stats"
    desc: "passive **Hardness** 18\n\n**HP** 72 (BT 36)\n\n**Resistances** Electricity 15\n\n**Immunities** Critical Hits, Object Immunities, Precision Damage"

  - name: "Reactive Charge"
    desc: "`pf2:r` (arcane) **Trigger** A creature without an Aspis Consortium badge approaches within 5 feet of a slab\n* * *\n\n**Effect** Both double doors leading out of the room shut and lock. While the trap is active, the doors must be battered open (Hardness 18; Panel HP 72 [BT 36]; DC 29 Athletics check to [[Actions/Force Open|Force Open]]). The closest symbol to the triggering creature shoots an electricity bolt attack at it. The trap then rolls initiative."

  - name: "No Multiple Attack Penalty"
    desc: "passive "
  - name: "Melee"
    desc: "Electrical Bolt +21 (range 40 feet) "

  - name: "Routine"
    desc: "(5 actions) Each disabled symbol reduces the trap's number of actions by 1.\n\nFor each of its actions, a different symbol shoots an electricity bolt at a random creature in the room. The trap doesn't take multiple attack penalties."
  - name: "Reset"
    desc: "The trap deactivates 1 round after it has no target creatures and resets after 1 minute."
```

```encounter-table
name: Scroll Shock Trap
creatures:
  - 1: Scroll Shock Trap
```

