---
title: Lichen Monstrosity
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #203: Shepherd of Decay
aliases: "Actor.zXH6daoQozoQzOVx" 
level: 11
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Lichen Monstrosity"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 26
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +26, __Ref__ +24, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 10"
perception:
  - name: ""
  - name: "Stealth DC 26" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A mass of petrified lichen takes the shape of a beast and lurches forward."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Survival check or DC 33 Thievery check (master) to scrape away lichen without being exposed, or DC 36 Medicine check or DC 36 Nature check (expert) to concoct a natural remedy and weaken the hazard; four total successes are required to disable it."
attacks:
  - name: ""

  - name: "Lurching Lichen"
    desc: "`pf2:r` **Trigger** Three or more creatures not infected with leechlichen enter the area of the hazard;\n* * *\n\n**Effect** The mass of lichen lurches forward, taking up one 5-foot square and forming a beast-like shape. The hazard rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The lichen monstrosity uses 3 actions to move, traveling up to 30 feet with each action and dealing 2d10+10 bludgeoning damage. Each creature in its path must attempt a DC 31 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is exposed to leechlichen.\n\n**Critical Failure** The creature takes double damage and is exposed to leechlichen. The results of its saving throw against the leechlichen are treated as one step worse. Each successful check to disable this hazard reduces its movement by 30 feet, and the fourth success disables it completely."
  - name: "Reset"
    desc: "The trap resets over the course of an hour."
```

```encounter-table
name: Lichen Monstrosity
creatures:
  - 1: Lichen Monstrosity
```

