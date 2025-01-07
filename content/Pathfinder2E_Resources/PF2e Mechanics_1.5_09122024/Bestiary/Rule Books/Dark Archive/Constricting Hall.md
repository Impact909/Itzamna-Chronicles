---
title: Constricting Hall
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.RBpQa1gnghZUg7VV" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Constricting Hall"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 21
sourcebook: "_Pathfinder Dark Archive_"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: " +21"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A hall's four walls become fluid and elastic when a creature reaches the hall's midpoint."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (trained) to stabilize each wall, or [[Spells/Dispel Magic|Dispel Magic]] (4th level; counteract DC 26) to counteract each wall"
attacks:
  - name: ""

  - name: "Lose Form"
    desc: "`pf2:r` (occult) **Trigger** A creature reaches the hall's midpoint\n* * *\n\n**Effect** The hall's walls lose their rigidity, becoming fluid and elastic. The hall becomes difficult terrain, and each creature in the hall is knocked [[Conditions/Prone|Prone]] unless they succeed at a DC 26 Reflex check save. The trap then rolls initiative."
  - name: "Melee"
    desc: "Wall +20 () "

  - name: "Routine"
    desc: "(4 actions) This trap loses 1 action each round for each wall that has been disabled. Each wall uses 1 action to slam back and forth rapidly, pummeling one creature in the hall with a wall Strike. On a hit, the target is additionally knocked [[Conditions/Prone|Prone]]. The walls distribute the attacks as evenly as possible among creatures in the hall, and the Strikes don't apply the trap's multiple attack penalty."
  - name: "Reset"
    desc: "1 hour"
```

```encounter-table
name: Constricting Hall
creatures:
  - 1: Constricting Hall
```

