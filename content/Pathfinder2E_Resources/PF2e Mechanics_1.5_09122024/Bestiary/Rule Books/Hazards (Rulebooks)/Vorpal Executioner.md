---
title: Vorpal Executioner
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.xNeDmMBF2h2uLV5V" 
level: 19
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Vorpal Executioner"
level: "Hazard 19"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 33
sourcebook: "_Pathfinder GM Core_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +32, __Ref__ +32, "
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120, per junction; __Hardness__ 30; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 43" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A wickedly sharp saw blade descends and travels along grooves in a complex path throughout the room, attempting to decapitate everyone within."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 41 Thievery check (expert) at four different junctions to jam all the saw blade's possible paths, preventing it from traveling through the room"
attacks:
  - name: ""

  - name: "Total Decapitation"
    desc: "`pf2:r` (attack, death) **Trigger** A creature attempts to exit the room.\n* * *\n\n**Effect** The saw blade travels along its path, making one Strike against each creature in the room, twisting and varying its height for a maximum chance of beheading its targets."
  - name: "Melee"
    desc: "Saw Blade +40 (deadly d12, death) "

  - name: "Decapitation"
    desc: "passive On a critical hit, a target must succeed at a DC 39 Fortitude check save or be decapitated, dying instantly unless it can survive without a head."

  - name: "No MAP"
    desc: "passive The saw blade Strikes do not apply a MAP."


  - name: "Reset"
    desc: "The trap resets over the course of the round and can be triggered again 1 round later."
```

```encounter-table
name: Vorpal Executioner
creatures:
  - 1: Vorpal Executioner
```

