---
title: Stabbing Sentinel
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #155: Lord of the Black Sands
aliases: "Actor.ZvjAVX4x5kTdIOCq" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Stabbing Sentinel"
level: "Hazard 18"


trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 35
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +36, __Ref__ +27, "
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120; __Hardness__ 30; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 45" 
    desc: "DC 45 Perception check (master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A petrified creature momentarily animates to attack an adjacent creature."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Thievery check (master) to remove the animating magic without triggering the trap, or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 38) to counteract the animating magic"
attacks:
  - name: ""

  - name: "Animated Attack"
    desc: "`pf2:r` (attack) **Trigger** A living or undead creature moves within 5 feet of the stabbing sentinel\n* * *\n\n**Effect** The stabbing sentinel animates, making one Strike against the triggering creature."
  - name: "Melee"
    desc: "Blade +38 () "

  - name: "Petrification Overcharge"
    desc: "passive On a critical hit, the target is [[Conditions/Petrified|Petrified]] for 1 round. Additionally, if another stabbing sentinel has already been triggered, that sentinel immediately resets. If no other stabbing sentinels have been triggered, then another random statue in the room becomes infused with animating magic and becomes another stabbing sentinel hazard (to a maximum of four at a time)."


  - name: "Reset"
    desc: "The magical energy that animates the statue builds up again over 24 hours and the trap resets."
```

```encounter-table
name: Stabbing Sentinel
creatures:
  - 1: Stabbing Sentinel
```

