---
title: Siphoning Spirit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Book of the Dead
aliases: "Actor.Mi0XxnI99Yl9O2xM" 
level: 19
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Siphoning Spirit"
level: "Hazard 19"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 40
sourcebook: "_Pathfinder Book of the Dead_"
perception:
  - name: ""
  - name: "Stealth DC 40" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A formless spirit drains life from the living, becoming progressively visible as its victims weaken."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Occultism check (expert) or DC 48 Religion check (expert) to weaken the spirit; four total successes are required to disable the haunt"
attacks:
  - name: ""

  - name: "Sudden Siphon"
    desc: "`pf2:r` (divine, void) **Trigger** A living creature passes within 15 feet of the spirit\n* * *\n\n**Effect** The invisible spirit latches onto the life essence of the living, dealing 4d10+20 void damage to all living creatures within 60 feet (DC 41 Fortitude check save). The haunt then rolls initiative."

  - name: "Routine"
    desc: "(1 action; death, divine, necromancy, void) The spirit inhales, siphoning the souls of the living and becoming more visible. Each creature within 60 feet takes 4d10+20 void damage, with a DC 41 Fortitude check save. If no creatures are within the area, the haunt moves up to 120 feet into the largest concentration of living creatures and then inhales.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and increases its [[Conditions/Drained|Drained]] value by 1, to a maximum of drained 4.\n\n**Critical Failure** The creature takes double damage and increases its drained value by 2, to a maximum of drained 4. If the creature was already drained 4, it dies."
  - name: "Reset"
    desc: "After 1 minute, the spirit is satiated, and the haunt deactivates as it returns to a resting state. Over the course of 1 hour, the spirit's siphoned life energy disperses and the haunt resets."
```

```encounter-table
name: Siphoning Spirit
creatures:
  - 1: Siphoning Spirit
```

