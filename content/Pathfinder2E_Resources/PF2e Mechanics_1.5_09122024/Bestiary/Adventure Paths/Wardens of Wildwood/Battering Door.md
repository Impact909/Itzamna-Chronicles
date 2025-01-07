---
title: Battering Door
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.sJ2Mb9sB57NIpvsM" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Battering Door"
level: "Hazard 9"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 23
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +21, __Ref__ +15, "
hp: 70
health:
  - name: ""
  - name: "HP"
    desc: "70; __Hardness__ 16; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Animated door slams into trespassers."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Diplomacy check or DC 30 Occultism check (master) to soothe the psychic impressions or DC 28 Thievery check (expert) to jam the door open"
attacks:
  - name: ""

  - name: "Batter Trespasser"
    desc: "`pf2:r` **Trigger** A living creature passes through the door\n* * *\n\n**Effect** The door slams into the triggering creature, dealing 4d10+26 bludgeoning damage (DC 28 Reflex check save)."


  - name: "Reset"
    desc: "The trap resets automatically."
```

```encounter-table
name: Battering Door
creatures:
  - 1: Battering Door
```

