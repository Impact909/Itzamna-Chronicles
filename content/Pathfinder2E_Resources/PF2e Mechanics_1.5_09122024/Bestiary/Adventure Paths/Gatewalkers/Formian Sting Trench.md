---
title: Formian Sting Trench
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #187: The Seventh Arch
aliases: "Actor.VbbuG8YeQfN5OJYi" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Formian Sting Trench"
level: "Hazard 4"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 0
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +8, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A thin layer of canvas conceals this 10-foot-square pit, the walls of which are studded with dagger-sized formian stingers. Creatures that fall into the trap risk being gouged by the poisonous barbs."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Thievery check (trained)"
attacks:
  - name: ""

  - name: "Entrench"
    desc: "`pf2:r` (attack) **Trigger** A creature walks onto the canvas\n* * *\n\n**Effect** The creature falls into the [[Conditions/Concealed|Concealed]] trench and takes falling damage (typically 10 bludgeoning). The creature is also gouged by three poisoned stingers as they fall. The creature can use the [[Actions/Grab an Edge|Grab an Edge]] reaction to avoid falling."
  - name: "Melee"
    desc: "Stinger +17 () "

  - name: "Formian Trench Poison"
    desc: "passive (poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison (1 round)\n\n**Stage 2** 1d6 poison and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** 1d6 poison, clumsy 1, and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 4** 2d6 poison, clumsy 1, and enfeebled 1 (1 round)"


  - name: "Reset"
    desc: "Creatures can still fall into the trap, but the canvas must be reset manually for the trap to become hidden again."
```

```encounter-table
name: Formian Sting Trench
creatures:
  - 1: Formian Sting Trench
```

