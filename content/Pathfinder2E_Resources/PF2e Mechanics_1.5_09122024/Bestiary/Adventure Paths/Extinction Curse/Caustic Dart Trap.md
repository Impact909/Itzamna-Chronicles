---
title: Caustic Dart Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #153: Life&#x27;s Long Shadows
aliases: "Actor.5oMy1woWUdbhCV65" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life's Long Shadows"
name: "Caustic Dart Trap"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #153: Life's Long Shadows_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +15, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80, per launching mechanism; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(expert) or DC 30 Perception check (expert) to notice the three launching mechanisms built into the wall"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three launching mechanisms built into the mudbrick walls expel darts containing acidic chemicals. All three launching mechanisms must be disabled or destroyed to deactivate the trap."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Thievery check (master) to sufficiently jam the tubes to make the trap unable to attack creatures in a single 5-foot square in the room, or DC 34 Crafting check (master) to alter one of the three launching mechanisms."
attacks:
  - name: ""

  - name: "Dart Barrage"
    desc: "`pf2:r` (attack) **Trigger** A creature reaches the midpoint of the hall\n* * *\n\n**Effect** The trap makes an acid dart against three different random creatures in the hall. The trap then rolls initiative."
  - name: "Melee"
    desc: "Caustic Dart +28 () "

  - name: "Routine"
    desc: "(3 actions) The trap uses each action for a caustic dart Strike. The trap loses 1 action for each launching mechanism that is broken or destroyed."
  - name: "Reset"
    desc: "The trap deactivates and resets 1 minute after no creatures are in area **C7**"
```

```encounter-table
name: Caustic Dart Trap
creatures:
  - 1: Caustic Dart Trap
```

