---
title: Flensing Chute
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #173: Doorway to the Red Star
aliases: "Actor.LCFTzJm1WHPWggZB" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Flensing Chute"
level: "Hazard 12"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 25
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The stairs collapse into a downward spiral."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 35 Thievery check (master) to decouple several mechanisms barely accessible through gaps between the shifting risers, or DC 38 Perception check to note which stairs have slightly different wear patterns to know which ones are safe to step on"
attacks:
  - name: ""

  - name: "Change to Chute"
    desc: "`pf2:r` **Trigger** A Small or larger creature approaches within 20 feet of the top of the stairs\n\n**Reaction** The stair risers shift downward, forming a steep ramp while exposing lines of razor-sharp blades.\n\nAll creatures on the stairs must succeed at a DC 32 Reflex check save or tumble down the chute, taking 2d6 bludgeoning damage + 4d12+26 slashing damage, and landing [[Conditions/Prone|Prone]] in area **A4**."


  - name: "Reset"
    desc: "The flensing chute resets automatically."
```

```encounter-table
name: Flensing Chute
creatures:
  - 1: Flensing Chute
```

