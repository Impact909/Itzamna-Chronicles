---
title: Flensing Blades
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.PYnIMSrqvSJRMW6D" 
level: 12
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Flensing Blades"
level: "Hazard 12"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 25
sourcebook: "_Pathfinder GM Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +27, __Ref__ +25, __Will__ +22"
hp: 100
health:
  - name: ""
  - name: "HP"
    desc: "100; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 15"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A whirling tornado of spectrally propelled glass and steel slices whatever it touches to ribbons."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 35 Thievery check (master) to precisely adjust the blades so that they destroy each other, or DC 38 Religion check (expert) to weaken the haunt; four successes are required to disable it"
attacks:
  - name: ""

  - name: "Whirling Blades"
    desc: "`pf2:r` **Trigger** Three or more creatures enter the area of the haunt\n* * *\n\n**Effect** Sharp fragments lift up from the ground and begin to spin in rapid circles taking up one 5-foot square. The haunt rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The tornado of blades uses 3 actions to move, traveling up to 30 feet with each action and dealing 2d10+10 slashing damage. Each creature in its path must attempt a DC 33 Reflex check.\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage plus 1d10 bleed.\n\n**Critical Failure** The creature takes double damage and 1d10 bleed. It also becomes [[Conditions/Wounded|Wounded 1]] (or increases its wounded value by 1, if it is already wounded).\n\nEach successful check to disable this hazard reduces the haunt's movement by 30 feet, and the fourth success disables it completely."
  - name: "Reset"
    desc: "The haunt draws jagged shards back into its area over the course of an hour, after which it can trigger again."
```

```encounter-table
name: Flensing Blades
creatures:
  - 1: Flensing Blades
```

