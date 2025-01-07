---
title: Wooden Bullets Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #178: Punks in a Powder Keg
aliases: "Actor.7UgxoSmdfSHyvF7g" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Wooden Bullets Trap"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +15, __Ref__ +5, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 5"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A hopper full of wooden sling bullets is attached to several launching devices, which spew the bullets at high velocity through various holes in the boards covering the window. A distinctive \"click\" and whirring sound indicate the trap has been sprung."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 17 Thievery check (trained) to reinforce the porch pressure sensor or DC 15 Crafting check (trained) to cover the holes launching the bullets"
attacks:
  - name: ""

  - name: "Auto-Sling"
    desc: "`pf2:r` **Trigger** A creature or object weighing at least 50 pounds is placed on the porch (marked \"T\" on the map)\n* * *\n\n**Effect** A stream of wooden sling bullets flies from a launcher. The trap Strikes the two nearest creatures and then rolls initiative."
  - name: "Melee"
    desc: "Wooden Bullet +12 (nonlethal, range 10 feet) "

  - name: "Routine"
    desc: "(2 actions) The wooden bullets trap Strikes the two nearest creatures. It ignores [[Conditions/Prone|Prone]] creatures as the bullets fly overhead."
  - name: "Reset"
    desc: "The trap stops after 10 rounds or when the weight on the porch is removed, whichever comes first. The trap can operate for a total of 10 rounds before its ammunition is exhausted."
```

```encounter-table
name: Wooden Bullets Trap
creatures:
  - 1: Wooden Bullets Trap
```

