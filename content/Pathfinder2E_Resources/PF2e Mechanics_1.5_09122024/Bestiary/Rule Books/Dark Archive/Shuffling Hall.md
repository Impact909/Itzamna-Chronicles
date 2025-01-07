---
title: Shuffling Hall
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Dark Archive
aliases: "Actor.d2a0UMgqzrCuZTHA" 
level: -1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Shuffling Hall"
level: "Hazard -1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 5
sourcebook: "_Pathfinder Dark Archive_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +2, __Ref__ +5, "
hp: 12
health:
  - name: ""
  - name: "HP"
    desc: "12; __Hardness__ 4; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: " +5"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four pressure plates along this mirrored hall rotate vertically when stepped on, sending a creature on the pressure plate tipping into an adjacent featureless room while simultaneously replacing the pressure plate and walls in the hall. Each pressure plate dumps creatures into a different room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 12 Thievery check to deactivate one pressure plate"
attacks:
  - name: ""

  - name: "Flip"
    desc: "`pf2:r` **Trigger** A creature steps on a pressure plate\n* * *\n\n**Effect** The floor and adjoining wall rotate up and over on a central axle, tipping the triggering creature into an adjacent featureless room and simultaneously replacing the pressure plate and wall with another set on the same axle. The triggering creature is pushed into an adjoining room, takes 1d8 bludgeoning damage, and lands [[Conditions/Prone|Prone]]. A creature who succeeds at a DC 19 Reflex check save takes no damage and rolls out of the way of the trap, returning to the space they were in before stepping on the pressure plate."


  - name: "Reset"
    desc: ""
```

```encounter-table
name: Shuffling Hall
creatures:
  - 1: Shuffling Hall
```

