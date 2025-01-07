---
title: Violet Mister
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #187: The Seventh Arch
aliases: "Actor.A6hXhTOUGQhpeqa4" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Violet Mister"
level: "Hazard 2"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +10, "
hp: 25
health:
  - name: ""
  - name: "HP"
    desc: "25; __Hardness__ 7; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(trained) to notice the trap's trigger-thread attached to the door"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Opening the door pulls a thread, which causes a plant mister to spray a cloud of poison into the triggering creature's face."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check to safely cut the thread"
attacks:
  - name: ""

  - name: "Poisoned Welcome"
    desc: "`pf2:r` **Trigger** A creature attempts to open the door\n* * *\n\n**Effect** Every creature within 10 feet of the door is exposed to violet venom poison."

  - name: "Violet Venom"
    desc: "passive (contact, poison) **Saving Throw** DC 17 Fortitude check;\n\n**Onset** 1 minute;\n\n**Maximum Duration** 6 rounds;\n\n**Stage 1** 1d6 poison plus [[Conditions/Enfeebled|Enfeebled 1]] (1 round);\n\n**Stage 2** 1d6 poison plus [[Conditions/Drained|Drained 1]] (1 round);\n\n**Stage 3** 2d6 poison plus enfeebled 1 (1 round)"



```

```encounter-table
name: Violet Mister
creatures:
  - 1: Violet Mister
```

