---
title: Befuddling Gas Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #165: Eyes of Empty Death
aliases: "Actor.esILHUhOHQl17S1k" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Befuddling Gas Trap"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 21
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +18, "
hp: 32
health:
  - name: ""
  - name: "HP"
    desc: "32; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: "+21 (expert) or DC 31 Perception check (expert) to notice the hidden override mechanism in the north wall"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Seven nozzles hidden within holes in the 15‑foot-high ceiling release a poison gas."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) to disable the hidden mechanism on the north wall, immediately sucking the gas from the room, or DC 29 Thievery check (expert) to adequately plug one of the seven nozzles. When all seven nozzles are plugged or destroyed, the trap is deactivated."
attacks:
  - name: ""

  - name: "Gas Release"
    desc: "`pf2:r` (inhaled, mental, poison) **Trigger** Both secret doors are closed and at least one creature is in the room\n* * *\n\n**Effect** Gas fills the chamber. Creatures within the chamber must succeed on a DC 30 Fortitude check save or become [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Stupefied|Stupefied 2]] on a critical failure). The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) The gas intensifies. Each creature in the room must make a DC 30 Fortitude check.\n* * *\n\n**Critical Success** The creature is unaffected and becomes temporarily immune to the gas for 1 hour, though if the creature has already been stupefied by the trap, that condition remains for its normal duration.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature becomes [[Conditions/Stupefied|Stupefied 1]] for 24 hours. If the target is already stupefied, the condition value increases by 1 (to a maximum of stupefied 4) and the target takes 8d6 mental damage.\n\n**Critical Effect** As failure, except the target takes double the mental damage."
  - name: "Reset"
    desc: "After an hour, the trap deactivates; the gas disperses slowly, and the doors can be opened again. After 24 hours, the gas builds up and the trap can be triggered again."
```

```encounter-table
name: Befuddling Gas Trap
creatures:
  - 1: Befuddling Gas Trap
```

