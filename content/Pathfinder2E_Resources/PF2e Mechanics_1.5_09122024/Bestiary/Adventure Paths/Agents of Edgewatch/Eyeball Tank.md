---
title: Eyeball Tank
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #161: Belly of the Black Whale
aliases: "Actor.P0VjRhvXN7MQKo1Z" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Eyeball Tank"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 31
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +29, __Ref__ +26, "
hp: 180
health:
  - name: ""
  - name: "HP"
    desc: "180; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 31" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A vat of thick glass stands 10 feet high and is filled with green slime and fist-sized eyeballs."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 38 Thievery check (master) or DC 34 Crafting check (expert) to acidify the slime inside the tank, destroying the eyeballs"
attacks:
  - name: ""

  - name: "Eye-Opener"
    desc: "`pf2:r` (emotion, mental) **Trigger** Three or more living creatures remain within 20 feet of the trap for 1 round\n* * *\n\n**Effect** The trap rolls initiative."
  - name: "Melee"
    desc: "Despair Ray +28 (emotion, mental, range increment 100 feet) "
  - name: "Melee"
    desc: "Feeblemind Ray +28 () "
  - name: "Melee"
    desc: "Spirit Blast Ray +28 (range increment 100 feet) "

  - name: "Spill Eyeballs"
    desc: "`pf2:r` **Trigger** The tank reaches its Broken Threshold\n* * *\n\n**Effect** The glass shatters, spilling eyeballs onto the floor in a 15-foot radius and casting _grease_(DC 33) on the affected area. The eyeball tank is permanently destroyed and can't be reset.**Reset** The trap can be reset by adding 100 new eyeballs to the tank and allowing them to grow in the slime for 1 week."

  - name: "Routine"
    desc: "(3 actions) Each round, the vat uses all three of its actions to shoot random eye rays at any living creatures (except Ixusoth) in range."

```

```encounter-table
name: Eyeball Tank
creatures:
  - 1: Eyeball Tank
```

