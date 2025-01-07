---
title: Spirit Cyclone
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Book of the Dead
aliases: "Actor.HRQpfxreGCXx2qBx" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Spirit Cyclone"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 20
sourcebook: "_Pathfinder Book of the Dead_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A cyclone of angry spirits surges around the area."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Occultism check (trained) or DC 30 Religion check (trained) to weaken the haunt; three total successes in any combination are required to disable the haunt"
attacks:
  - name: ""

  - name: "Gather Spirit"
    desc: "`pf2:r` **Trigger** Two or more creatures enter the area\n* * *\n\n**Effect** A spiraling column of spirits gather, becoming a whirling cyclone of souls 10 feet wide and 60 feet tall. The haunt then rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The spirit cyclone uses 3 actions to move, traveling up to 30 feet with each action and dealing 2d10+13 void damage to each creature in its path (DC 32 Reflex check save). A creature needs to attempt only one save during the cyclone's movement, even if the cyclone moves over its space more than once. On a critical failure, a creature is swept up into the cyclone, becoming [[Conditions/Grabbed|Grabbed]] ([[Actions/Escape|Escape]] DC 32). A creature grabbed by the cyclone moves along with the cyclone and takes 1d10+6 void damage at their beginning of its turn, and it must attempt a Reflex save against the cyclone on the cyclone's turn, no matter where the cyclone moves. A creature that successfully Escapes from the cyclone falls from a height of 1d12 x 5 feet."
  - name: "Reset"
    desc: "The spirit cyclone disperses after 1 minute and resets after 1 day."
```

```encounter-table
name: Spirit Cyclone
creatures:
  - 1: Spirit Cyclone
```

