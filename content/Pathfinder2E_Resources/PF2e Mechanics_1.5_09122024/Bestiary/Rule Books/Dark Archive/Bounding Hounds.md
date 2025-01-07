---
title: Bounding Hounds
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.7dtSEvPudumcGTtY" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Bounding Hounds"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 27
sourcebook: "_Pathfinder Dark Archive_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +20, __Ref__ +26, __Will__ +20"
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60, 60 HP per hound; __Immunities__  object immunities; __Resistances__ all damage 10 (except ghost touch; double resistance vs. non-magical)"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: " +27"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three phantom hounds chase down intruders, damaging any they pass through."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 36 Nature check (expert) to calm each hound, or DC 38 Occultism check (master) to banish each hound"
attacks:
  - name: ""

  - name: "Bay"
    desc: "`pf2:r` (sonic) **Trigger** A creature enters the area\n* * *\n\n**Effect** The hounds manifest and bay loudly, dealing 3d10 + 16 sonic damage to all creatures within 30 feet of the hounds (DC 33 Fortitude check). On a failed check, a creature is additionally [[Conditions/Frightened|Frightened 2]]. The trap then rolls initiative."

  - name: "Routine"
    desc: "(9 actions) The trap loses 3 actions each round for each hound disabled. Each hound uses three actions to Stride 40 feet after creatures in the room, passing through corporeal creatures during this movement if possible. Each creature the hound moves through during its movement takes 2d8 + 7 void damage (DC 37 Reflex check negates). A creature can only be damaged by each hound once each round, no matter how many times the hound moves through their space."
  - name: "Reset"
    desc: "1 hour"
```

```encounter-table
name: Bounding Hounds
creatures:
  - 1: Bounding Hounds
```

