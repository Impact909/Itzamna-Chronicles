---
title: Deadly Workshop
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: The Enmity Cycle
aliases: "Actor.7UaRZZXkEhmuLKKI" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Enmity Cycle"
name: "Deadly Workshop"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 6
sourcebook: "_Pathfinder Adventure: The Enmity Cycle_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +14, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, to destroy the chains and disable the trap; __Hardness__ 14; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 6" 
    desc: "(expert) to notice the blades embedded in the chains and the complex system of pulleys connecting them"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Swinging bladed chains whip through the entire workshop."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Thievery check (expert) on the control panel on the raised platform deactivates the trap."
attacks:
  - name: ""

  - name: "Swinging Blades"
    desc: "`pf2:r` (attack) **Trigger** Two or more creatures enter the workshop or end their turn in the workshop\n* * *\n\n**Effect** The trap makes a slashing blade Strike against the triggering creatures, then rolls initiative."
  - name: "Melee"
    desc: "Slashing Blade +15 () "

  - name: "No MAP"
    desc: "passive This trap doesn't take a multiple attack penalty."

  - name: "Routine"
    desc: "(1 action) The trap swings one slashing blade against every creature in the workshop as 1 action. The entire workshop is treated as difficult terrain because of the sheer number of slashing chains. This trap doesn't take a multiple attack penalty."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 minute."
```

```encounter-table
name: Deadly Workshop
creatures:
  - 1: Deadly Workshop
```

