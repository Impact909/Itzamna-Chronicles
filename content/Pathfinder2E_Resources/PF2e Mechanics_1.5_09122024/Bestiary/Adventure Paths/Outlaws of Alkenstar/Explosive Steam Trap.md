---
title: Explosive Steam Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #179: Cradle of Quartz
aliases: "Actor.tcw29lwzX6Df1HLt" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #179: Cradle of Quartz"
name: "Explosive Steam Trap"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #179: Cradle of Quartz_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +15, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 8; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained) to find the desk switch; DC 28 Perception check (expert) to find the trapdoor and charge"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A black‑powder charge fastened to a trapdoor (marked with a \"T\" on the map) blows a hole in a steam tunnel, filling the room with superheated steam."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to disarm the desk switch; DC 28 Thievery check (expert) to disarm the trapdoor charge"
attacks:
  - name: ""

  - name: "Explosive Charge"
    desc: "`pf2:r` **Trigger** The desk switch is pressed or the trapdoor is opened\n* * *\n\n**Effect** The charge on the door explodes. All creatures within 10 feet take 2d10+6 fire damage and 1d10+3 piercing damage, and 1d6 bleed (DC 22 Reflex check). The room is filled with steam, making all creatures within the room [[Conditions/Concealed|Concealed]]. The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) The trapdoor emits a jet of superheated steam. Each creature in the room must attempt a DC 28 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d10+3 fire damage.\n\n**Failure** The creature takes 2d10+6 fire damage and is [[Conditions/Blinded|Blinded]] for 1 round.\n\n**Critical Failure** The creature takes 2d10+6 fire damage, is [[Conditions/Fatigued|Fatigued]], and is blinded for 1 round."

```

```encounter-table
name: Explosive Steam Trap
creatures:
  - 1: Explosive Steam Trap
```

