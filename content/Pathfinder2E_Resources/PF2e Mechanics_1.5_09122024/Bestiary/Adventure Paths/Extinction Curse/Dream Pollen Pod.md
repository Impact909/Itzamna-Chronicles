---
title: Dream Pollen Pod
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #151: The Show Must Go On
aliases: "Actor.7r2A5wsisWCfjKOt" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Dream Pollen Pod"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[trap]]
modifier: 12
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +3, "
hp: 32
health:
  - name: ""
  - name: "HP"
    desc: "32; __Hardness__ 1; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 12" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four magical plants inside the wagon release hallucinogenic pollen when disturbed."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to carefully remove a pollen pod or DC 18 Nature check (trained) to prevent a pod from bursting."
attacks:
  - name: ""

  - name: "Pollen Burst"
    desc: "`pf2:r` **Trigger** The wagon door is opened or the pods are disturbed\n* * *\n\n**Effect** A pod makes a pollen spray Strike against an adjacent creature or the creature that opened the door, the door falls off the wagon, and the trap rolls initiative."
  - name: "Melee"
    desc: "Pollen Spray +12 (range increment 20 feet) "

  - name: "Hallucinogenic Pollen"
    desc: "passive A creature hit by the trap's pollen spray must succeed at a DC 20 Will check save or it is [[Conditions/Confused|Confused]] for 1 round and takes a -2 status penalty to Perception checks and saves against mental effects for 1d4 hours. On a critical failure, the penalty is instead -4.\n\n[[Bestiary Effects/Effect_ Hallucinogenic Pollen (Failure)|Effect: Hallucinogenic Pollen (Failure)]]\n\n[[Bestiary Effects/Effect_ Hallucinogenic Pollen (Critical Failure)|Effect: Hallucinogenic Pollen (Critical Failure)]]"

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action each turn for each removed or disabled pollen pod. The trap doesn't take a multiple attack penalty."
  - name: "Reset"
    desc: "The trap resets after 1 hour, when the pods have regrown additional pollen. If all the pods are removed or disabled, the trap doesn't reset."
```

```encounter-table
name: Dream Pollen Pod
creatures:
  - 1: Dream Pollen Pod
```

