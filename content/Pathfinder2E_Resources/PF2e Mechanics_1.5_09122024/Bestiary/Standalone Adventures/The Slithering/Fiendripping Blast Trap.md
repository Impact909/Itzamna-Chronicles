---
title: Fiendripping Blast Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: The Slithering
aliases: "Actor.w4QtlitB3V79pb2z" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Fiendripping Blast Trap"
level: "Hazard 7"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder Adventure: The Slithering_"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A blast of energy damages all creatures within 20 feet, with particularly severe damage to fiends."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Thievery check (expert) to identify the proper sequence of buttons in the divots, or [[Spells/Dispel Magic|Dispel Magic]] (4th level; counteract DC 25) to suppress the magical effect for 1 hour"
attacks:
  - name: ""

  - name: "Forceful Blast"
    desc: "`pf2:r` (divine) **Trigger** The door is touched without first pressing the correct sequence of buttons\n* * *\n\n**Effect** A blast of energy ripples outward from the door, dealing 4d10 force damage to all creatures within 20 feet and forcing them to make a DC 25 Fortitude check save.\n\nFiends treat the result of their saving throw as one degree worse.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** The creature takes double damage and is [[Conditions/Sickened|Sickened 2]]; while it is sickened, it's also [[Conditions/Slowed|Slowed 1]]."


  - name: "Reset"
    desc: "The trap resets after 1 hour."
```

```encounter-table
name: Fiendripping Blast Trap
creatures:
  - 1: Fiendripping Blast Trap
```

