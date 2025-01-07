---
title: Razor Snare
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.39aEKhkSjY7je2hc" 
level: 4
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Razor Snare"
level: "Hazard 4"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +8, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: " +15"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Slender razor wire snags a creature, yanking its feet to knock it down."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Survival check or DC 22 Thievery check (trained) to snip the wire without getting snared"
attacks:
  - name: ""

  - name: "Snag"
    desc: "`pf2:r` **Trigger** A creature steps into the square with the snare tripwire\n* * *\n\n**Effect** The snare makes a snare Strike against the triggering creature."
  - name: "Melee"
    desc: "Snare +15 () The target is [[Conditions/Grabbed|Grabbed]] ([[Actions/Escape|Escape]] DC 23). On a critical hit, the target is also knocked [[Conditions/Prone|Prone]]."



```

```encounter-table
name: Razor Snare
creatures:
  - 1: Razor Snare
```

