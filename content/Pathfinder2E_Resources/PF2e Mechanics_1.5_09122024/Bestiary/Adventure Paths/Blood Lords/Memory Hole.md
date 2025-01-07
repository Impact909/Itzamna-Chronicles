---
title: Memory Hole
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #183: Field of Maidens
aliases: "Actor.9S3G5OntXAhDayvP" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Memory Hole"
level: "Hazard 9"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 20
sourcebook: "_Pathfinder #183: Field of Maidens_"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Anyone looking into the hole has memories sucked from their head."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Deception check (master) to feed the pit false thoughts that plug it, or DC 28 Occultism check (expert) or [[Spells/Dispel Magic|Dispel Magic]] (4th level; counteract DC 27) to drain the pit's magic"
attacks:
  - name: ""

  - name: "Drink Thoughts"
    desc: "`pf2:r` **Trigger** A creature looks into the pit\n\n**Effect** Ephemeral energies pour from the creature's head, and the creature must attempt a DC 30 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\n**Failure** The creature is [[Conditions/Stupefied|Stupefied 2]] for 1 hour and loses 1 minute of recent memories (a memory of the GM's choosing within the last 24 hours).\n\n**Critical Failure** As failure, but [[Conditions/Stupefied|Stupefied 3]]."


  - name: "Reset"
    desc: "The trap resets after 1 hour if it's not disabled."
```

```encounter-table
name: Memory Hole
creatures:
  - 1: Memory Hole
```

