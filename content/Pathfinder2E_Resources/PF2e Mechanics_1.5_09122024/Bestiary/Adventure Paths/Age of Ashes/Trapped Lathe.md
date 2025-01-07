---
title: Trapped Lathe
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #147: Tomorrow Must Burn
aliases: "Actor.XynuuIprU12u1Vuq" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Trapped Lathe"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 19
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +14, "
hp: 72
health:
  - name: ""
  - name: "HP"
    desc: "72; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(expert); DC 29 Perception check to notice the line of cord running from the lathe's trigger toward the door to area **A2**."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The powered lathe's springs have been critically overwound so that when jostled or triggered, the lathe unwinds violently, hurling blades, gears, and sharp shards of metal around the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 31 Thievery check (expert) on the lathe releases the tension on its springs without unleashing its blades and gears."
attacks:
  - name: ""

  - name: "Unleash Fragments"
    desc: "`pf2:r` **Trigger** The lathe is jostled or damaged, or its trigger is remotely pulled.\n* * *\n\n**Effect** The trap makes a sharpened fragment Strike against a random target in area **A1**, then rolls for initiative."
  - name: "Melee"
    desc: "Sharpened Fragment +26 () "

  - name: "Persistent Bleed Critical"
    desc: "passive The sharpened fragments deal 1d8 bleed on a critical hit."

  - name: "Routine"
    desc: "(4 actions) The lathe attempts four sharpened fragment attacks against creatures in the room, selecting a target randomly from all available targets in area A1. The trap does not take multiple attack penalties for any of its attacks. The trap loses 1 action each turn as its springs wind down, and becomes disabled when it has 0 actions."

```

```encounter-table
name: Trapped Lathe
creatures:
  - 1: Trapped Lathe
```

