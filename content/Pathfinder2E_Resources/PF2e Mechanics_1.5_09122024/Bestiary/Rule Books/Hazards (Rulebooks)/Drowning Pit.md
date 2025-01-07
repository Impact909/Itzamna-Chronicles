---
title: Drowning Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.vMsmgtTpUl6KwMT6" 
level: 3
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Drowning Pit"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder GM Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +5, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60, Spout Hardness 8, Spout HP 32 (BT 16); __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained); DC 22 Perception check (expert) to notice the water spouts once the pit opens"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A trapdoor covers a 10-foot-square pit that's 30 feet deep and has 5 feet of water at the bottom. Four water spouts in the walls connect to hidden water tanks. Each water spout extends out of a different wall, 6 inches from the top of the pit."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to seal each water spout, DC 22 Thievery check (trained) to open the trapdoor, or DC 22 Athletics check to [[Action Macros/Force Open_ Athletics|Force Open: Athletics]] the trapdoor"
attacks:
  - name: ""

  - name: "Pitfall"
    desc: "`pf2:r` **Trigger** A creature walks onto the trapdoor\n* * *\n\n**Effect** The triggering creature falls in and takes damage from the fall, reduced by 5 feet for falling into the water (typically 12 bludgeoning damage). A creature can [[Actions/Grab an Edge|Grab an Edge]] to avoid falling. The trapdoor then slams shut, and the hazard rolls initiative."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action each turn for each disabled water spout. On each of the trap's actions, a spout pours water, increasing the depth of the water by 5 feet. Once the pit is full of water, the pit stops using actions, but creatures in the pit begin drowning."
  - name: "Reset"
    desc: "The trap can be reset if the door is manually reengaged and the water tanks are refilled; it can be reset without draining the pit, but doing so renders the pit less effective."
```

```encounter-table
name: Drowning Pit
creatures:
  - 1: Drowning Pit
```

