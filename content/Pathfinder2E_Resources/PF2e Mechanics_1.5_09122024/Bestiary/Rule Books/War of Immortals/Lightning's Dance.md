---
title: Lightning's Dance
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - kaiju
  - mythic
  - primal
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder War of Immortals
aliases: "Actor.hcD4gW4xM5OtbHyn" 
level: 11
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder War of Immortals"
name: "Lightning's Dance"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[kaiju]]
trait_02: [[mythic]]
trait_03: [[primal]]
modifier: 10
sourcebook: "_Pathfinder War of Immortals_"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(expert) or DC 33 Perception check (master) to notice sparks dancing around normally non-conductive surfaces"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Electricity suffuses an area where Agyra has used her lightning breath multiple times."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 35 Crafting check (master) to fashion a makeshift lightning rod, DC 33 Nature check (expert) to dissipate the electrical charge harmlessly into the air."
attacks:
  - name: ""

  - name: "Static Shock"
    desc: "`pf2:r` (electricity) **Trigger** A creature approaches within 10 feet of the hazard's center\n* * *\n\n**Effect** Electricity wells up from the ground and nearby material. Each creature in the hazard's area must attempt a DC 33 Fortitude check save, and the hazard then rolls initiative. A character wearing metal armor or wielding a metal shield or weapon of at least 1 Bulk treats the result of their saving throw as one step worse.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Clumsy|Clumsy 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Clumsy|Clumsy 2]] for 2 rounds.\n\n**Critical Failure** The creature is clumsy 2 for 4 rounds and [[Conditions/Stunned|Stunned 1]] for 1 round."
  - name: "Melee"
    desc: "Lightning Bolt +24 (range increment 120 feet) "

  - name: "Routine"
    desc: "(2 actions) Bolts of lightning flash out. The hazard makes two lightning bolt Strikes at two different creatures within 120 feet of the hazard's center. If only one creature is in range, the hazard makes only one Strike."
  - name: "Reset"
    desc: "The hazard deactivates and immediately resets if has no targets for 1 round; it also resets if Agyra uses her lightning breath multiple times in a single combat in the area."
```

```encounter-table
name: Lightning's Dance
creatures:
  - 1: Lightning's Dance
```

