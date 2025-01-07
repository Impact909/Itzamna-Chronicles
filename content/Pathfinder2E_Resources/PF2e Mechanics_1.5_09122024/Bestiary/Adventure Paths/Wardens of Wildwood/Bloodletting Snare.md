---
title: Bloodletting Snare
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.dkvls9Bzm90pUHd4" 
level: 6
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Bloodletting Snare"
level: "Hazard 6"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +11, "
hp: 48
health:
  - name: ""
  - name: "HP"
    desc: "48; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 28" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Slender razor wire snags a creature, hauling them up into the air while causing deep, bloody wounds."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Survival check (expert) or DC 25 Thievery check (expert) to snip the wire without getting snared"
attacks:
  - name: ""

  - name: "Snare"
    desc: "`pf2:r` **Trigger** A creature steps into the square with the snare tripwire\n* * *\n\n**Effect** The bloodletting snare makes a snare Strike against the triggering creature."
  - name: "Melee"
    desc: "Snare +20 (deadly d10) The target is [[Conditions/Grabbed|Grabbed]] and pulled off the ground ([[Actions/Escape|Escape]] DC 26). The persistent bleed can't be stopped while the creature is grabbed."



```

```encounter-table
name: Bloodletting Snare
creatures:
  - 1: Bloodletting Snare
```

