---
title: Green Slime
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

source: Pathfinder Gamemastery Guide
aliases: "Actor.I7fB1zcb0go7MX6e" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Green Slime"
level: "Hazard 9"


trait_01: [[environmental]]
modifier: 20
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +25, __Ref__ +15, "
hp: 200
health:
  - name: ""
  - name: "HP"
    desc: "200; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ cold 20, fire 20"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A caustic green film clings to the ceiling above, watching for prey to pass beneath it."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Survival check (expert) to carefully peel the slime off the ceiling without touching it"
attacks:
  - name: ""

  - name: "Dissolving Ambush"
    desc: "`pf2:r` **Trigger** A creature walks beneath the slime.\n* * *\n\n**Effect** The green slime drops on top of the creature, attempting to dissolve it into a nutritious slurry. The target must attempt a DC 28 Reflex check save.\n* * *\n\n**Critical Success** The target leaps out of the way, and it is unaffected.\n\n**Success** A small amount of the slime splashes onto the target. The target is drained 1.\n\n**Failure** The slime lands on its target. The target is drained 1, and this condition value increases by 1 at the end of its turn each round until the slime is removed. If the target reaches drained 4, the next time its drained value would increase, it dies and collapses into a slurry of nutrients. A slime covering a target can no longer be removed through Survival checks, and damage dealt to the slime is also dealt to the target (applying the target's immunities, weaknesses, and resistances rather than those of the green slime).\n\n**Critical Failure** The slime completely coats its target. This has the same effect as a failure, except the target is immediately drained 2, becomes drained 4 after 1 round, and dies after 2 rounds."


  - name: "Reset"
    desc: "1 hour, as the slime feasts and then slowly creeps back up to the ceiling"
```

```encounter-table
name: Green Slime
creatures:
  - 1: Green Slime
```

