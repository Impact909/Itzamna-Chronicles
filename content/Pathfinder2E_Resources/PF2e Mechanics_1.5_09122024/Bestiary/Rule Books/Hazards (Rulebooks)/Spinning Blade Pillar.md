---
title: Spinning Blade Pillar
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.mH4igpB7ktFmNmcz" 
level: 4
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Spinning Blade Pillar"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder GM Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +12, "
hp: 48
health:
  - name: ""
  - name: "HP"
    desc: "48, Panel Hardness: 5, Panel HP: 20 (BT 10); __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained) or DC 26 Perception check (expert) to notice the control panel"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A metal pole with three razor-sharp spinning blades is hidden in the floor, connected to trigger plates in up to eight floor tiles and a hidden control panel within 30 feet."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 21 Thievery check (trained) twice on the pillar, or DC 19 Thievery check (expert) once on the control panel deactivates the whole trap. Breaking the control panel prevents anyone from disabling the trap using the control panel and prevents the trap from deactivating automatically."
attacks:
  - name: ""

  - name: "Rising Pillar"
    desc: "`pf2:r` (attack) **Trigger** A creature steps on one of the trapped floor tiles\n* * *\n\n**Effect** The trap pops up in a grid intersection and makes a spinning blade Strike against one adjacent creature (if any), then rolls initiative."

  - name: "Speed"
    desc: "passive 10 feet"
  - name: "Melee"
    desc: "Spinning Blade +12 () "

  - name: "Routine"
    desc: "(3 actions) The trap uses its first action to make a spinning blade Strike against each adjacent creature, its second action to move straight in a random direction (roll 1d4 to determine the direction), and its third to make a spinning blade Strike against each adjacent creature. This trap doesn't take a multiple attack penalty."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 minute."
```

```encounter-table
name: Spinning Blade Pillar
creatures:
  - 1: Spinning Blade Pillar
```

