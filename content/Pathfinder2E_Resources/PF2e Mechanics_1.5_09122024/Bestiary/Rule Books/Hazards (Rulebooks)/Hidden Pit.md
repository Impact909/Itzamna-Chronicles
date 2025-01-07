---
title: Hidden Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.Tvr0QOydSLRgpOZH" 
level: 0
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Hidden Pit"
level: "Hazard 0"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder GM Core_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +1, __Ref__ +1, "
hp: 12
health:
  - name: ""
  - name: "HP"
    desc: "12; __Hardness__ 3; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(or 0 if the trapdoor is disabled or broken)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A wooden trapdoor covers a pit that's 10 feet square and 20 feet deep."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 12 Thievery check to remove the trapdoor"
attacks:
  - name: ""

  - name: "Pitfall"
    desc: "`pf2:r` **Trigger** A creature walks onto the trapdoor.\n* * *\n\n**Effect** The triggering creature falls in and takes falling damage (typically 10 bludgeoning damage). That creature can use the [[Actions/Grab an Edge|Grab an Edge]] reaction to avoid falling."


  - name: "Reset"
    desc: "Creatures can still fall into the trap, but the trapdoor must be reset manually for the trap to become hidden again."
```

```encounter-table
name: Hidden Pit
creatures:
  - 1: Hidden Pit
```

