---
title: Reservoir Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #187: The Seventh Arch
aliases: "Actor.a3AYpcpLG7UrvBTa" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Reservoir Trap"
level: "Hazard 1"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +3, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, See Pipes; __Hardness__ 7; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained); DC 19 Perception check (expert) to notice the water tank bulging under the immense pressure"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Pipes extending from a pressurized water tank spray flesh-cutting jets of water at unwary passersby."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to safely puncture a pipe, or Engineering Lore (trained) to find and turn a pressure release valve; any combination of three punctured pipes or turned valves disables the trap"
attacks:
  - name: ""

  - name: "Pipes"
    desc: "passive **Pipe Hardness** 7, **Pipe HP** 30 (BT 15)"

  - name: "Water Jets"
    desc: "`pf2:r` **Trigger** A creature steps on a floor space in this room\n* * *\n\n**Effect** Seals on the water pipes burst, issuing forth high-pressure water jets in random directions. The hazard makes a water jet Strike against the triggering creature. The hazard rolls initiative."

  - name: "Violent Deluge"
    desc: "`pf2:r` **Trigger** The water tank is broken or destroyed\n* * *\n\n**Effect** A torrent of water bursts from the shattered tank, dealing 3d8 bludgeoning to each creature within 15 feet (basic DC 22 Reflex check save). The trap is then disabled."
  - name: "Melee"
    desc: "Water Jet +11 (water) "

  - name: "No MAP"
    desc: "passive No multiple attack penalty applies to Water Jet strikes"

  - name: "Routine"
    desc: "(3 actions) For each pipe destroyed or disabled, the trap loses 1 action. On each of the trap's actions, the trap targets a random creature in the room with a water jet Strike."
  - name: "Reset"
    desc: "The trap deactivates after 5 rounds. It cannot be reactivated until the reservoir is refilled, which takes an average of 5 days."
```

```encounter-table
name: Reservoir Trap
creatures:
  - 1: Reservoir Trap
```

