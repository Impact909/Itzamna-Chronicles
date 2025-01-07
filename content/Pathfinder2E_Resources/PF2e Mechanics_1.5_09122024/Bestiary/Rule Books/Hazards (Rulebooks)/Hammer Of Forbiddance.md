---
title: Hammer Of Forbiddance
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.wHBiLkw3fiEMJLxh" 
level: 11
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Hammer Of Forbiddance"
level: "Hazard 11"


trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 20
sourcebook: "_Pathfinder GM Core_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +24, __Ref__ +15, "
hp: 88
health:
  - name: ""
  - name: "HP"
    desc: "88, Joint Hardness:16, Joint HP: 64 (BT 32); __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An enormous hammer at an edifice's entrance swings down in an attempt to damage a creature entering an area, push it back, and prevent it from going any further."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (expert) once on the hammer itself and once on its joint to prevent the hammer from swinging"
attacks:
  - name: ""

  - name: "Forbid Entry"
    desc: "`pf2:r` (attack, divine) **Trigger** A creature attempts to enter through the entrance.\n* * *\n\n**Effect** The hammer swings down, making a Strike against the triggering creature."
  - name: "Melee"
    desc: "Hammer +28 () On a hit, the target is knocked back 10 feet and must succeed at a DC 30 Will check or be unable to enter the edifice through any entrance for 24 hours (on a critical hit, the target automatically fails the Will save); no multiple attack penalty"


  - name: "Reset"
    desc: "The trap resets over the course of the round, and is ready to swing again 1 round later."
```

```encounter-table
name: Hammer Of Forbiddance
creatures:
  - 1: Hammer Of Forbiddance
```

