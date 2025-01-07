---
title: Shadow Roil
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - shadow
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.Ye2MAoxVK5x2MRr4" 
level: 10
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Shadow Roil"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[shadow]]
trait_03: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #202: Severed at the Root_"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A cyclone of living shadows and planar magic surges around the area, attracted to living creatures."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Arcana check or DC 32 Occultism check (expert) to weaken the tornado; three successes in any combination are required to disable the trap."
attacks:
  - name: ""

  - name: "Touch Down"
    desc: "`pf2:r` **Trigger** Two or more living creatures enter the area\n* * *\n\n**Effect** A spiraling column of shadows and crackling planar magic gathers 20 feet away, becoming a whirling cyclone of darkness 15 feet wide and 100 feet tall. The trap then rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The cyclone uses 3 actions to move, traveling up to 30 feet with each action and dealing 2d12+13 slashing damage to each creature in its path (DC 33 Reflex check save). A creature needs to attempt only one save during the cyclone's movement, even if the cyclone moves over its space more than once. On a critical failure, a creature is swept up into the cyclone, becoming [[Conditions/Grabbed|Grabbed]] ([[Actions/Escape|Escape]] DC 33). A creature grabbed by the cyclone moves along with the cyclone and takes 1d12+7 additional slashing damage at the beginning of its turn, and it must attempt the basic Reflex save against the cyclone on the cyclone's turn, no matter where the cyclone moves. A creature that successfully Escapes from the cyclone falls from a height of 1d20 × 5 feet."
  - name: "Reset"
    desc: "The cyclone disperses after 1 minute and resets after 1 day."
```

```encounter-table
name: Shadow Roil
creatures:
  - 1: Shadow Roil
```

