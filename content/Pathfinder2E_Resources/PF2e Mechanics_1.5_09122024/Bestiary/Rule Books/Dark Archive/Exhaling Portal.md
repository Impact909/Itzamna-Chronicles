---
title: Exhaling Portal
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.31pX1qafl9dHw6F3" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Exhaling Portal"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 23
sourcebook: "_Pathfinder Dark Archive_"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: " +23"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Magic runes carved into a doorframe connect a door to the Plane of Air when opened, blowing creatures down the connecting hall."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Thievery check (expert) twice to scratch out the runes, or [[Spells/Dispel Magic|Dispel Magic]] (5th level; counteract DC 30) to counteract the planar runes; DC 32 Athletics check to shut the door if it's open (using Athletics only stops the trap, it doesn't fully disable it)"
attacks:
  - name: ""

  - name: "Gust"
    desc: "`pf2:r` (air) **Trigger** A creature opens the door\n* * *\n\n**Effect** The hall is buffeted by powerful winds for as long as the door remains open. A creature must succeed at a DC 32 Athletics check check to move toward the door. A creature who fails at this check is pushed back 5 feet and falls [[Conditions/Prone|Prone]].\n\nAdditionally, the triggering creature is blasted by a powerful gust of wind and must attempt a DC 32 Fortitude check save. The trap then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is pushed back 5 feet.\n\n**Failure** The creature is pushed back 10 feet.\n\n**Critical Failure** The creature is pushed back 10 feet and knocked [[Conditions/Prone|Prone]]."

  - name: "Routine"
    desc: "(1 action) The trap uses 1 action to blow powerful winds down the hall. Each creature in the hall must attempt a DC 32 Fortitude check save with the same results as Gust. If this forced movement would cause a creature to collide with a solid object or fall downstairs or out a window, that creature takes an additional 2d10 + 11 bludgeoning damage (or 20 bludgeoning damage due to a fall)."
  - name: "Reset"
    desc: "Automatic after the door is shut"
```

```encounter-table
name: Exhaling Portal
creatures:
  - 1: Exhaling Portal
```

