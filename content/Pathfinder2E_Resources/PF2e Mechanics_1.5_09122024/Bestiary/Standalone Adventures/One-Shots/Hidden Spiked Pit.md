---
title: Hidden Spiked Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard

source: Pathfinder Adventure: A Few Flowers More
aliases: "Actor.3jNpui6CmkXRkafh" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: A Few Flowers More"
name: "Hidden Spiked Pit"
level: "Hazard 2"


trait_01: [[mechanical]]
modifier: 11
sourcebook: "_Pathfinder Adventure: A Few Flowers More_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +5, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 7; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: "(trained) or DC 0 if the trapdoor is disabled or broken"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A wooden trapdoor covers a pit that's 10 feet square and 20 feet deep. Knives are arrayed at the bottom of the trap, impaling anyone who falls on them."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to remove the trapdoor"
attacks:
  - name: ""

  - name: "Pitfall"
    desc: "`pf2:r` **Trigger** A creature walks onto the trapdoor\n* * *\n\n**Effect** The triggering creature falls in and takes falling damage (10 bludgeoning damage) as well as 2d6 piercing damage from falling on to the knives. That creature can use the [[Actions/Grab an Edge|Grab an Edge]] reaction to avoid falling."


  - name: "Reset"
    desc: "Creatures can still fall into the trap, but the trapdoor must be reset manually for the trap to become [[Conditions/Hidden|Hidden]] again."
```

```encounter-table
name: Hidden Spiked Pit
creatures:
  - 1: Hidden Spiked Pit
```

