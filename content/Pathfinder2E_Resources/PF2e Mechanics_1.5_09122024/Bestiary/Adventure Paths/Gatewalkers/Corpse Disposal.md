---
title: Corpse Disposal
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #187: The Seventh Arch
aliases: "Actor.idWvShMVH0SfKK3y" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Corpse Disposal"
level: "Hazard 2"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +7, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 9; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: "(or 0 if the trapdoor is disabled or broken)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A wooden trapdoor conceals a spike-filled pit 10 feet square and 20 feet deep. The DC to Climb out of the pit is DC 10 Athletics check."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to jam the trapdoor open"
attacks:
  - name: ""

  - name: "Dispose"
    desc: "`pf2:r` **Trigger** A creature steps onto the trapdoor (marked \"T\" on the map)\n* * *\n\n**Effect** The triggering creature falls into the pit. The creature can use the [[Actions/Grab an Edge|Grab an Edge]] reaction to avoid falling. Failing that, the creature falls 20 feet (taking 10 bludgeoning from the fall) and takes 3d6 piercing from the metal spikes jutting up from the pit's floor. A creature who takes damage from the spikes is exposed to tetanus."

  - name: "Tetanus"
    desc: "passive (disease) **Saving Throw** DC 14 Fortitude check\n\n**Onset** 10 days\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 week)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and can't speak (1 day)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] with spasms (1 day)\n\n**Stage 4** death"



```

```encounter-table
name: Corpse Disposal
creatures:
  - 1: Corpse Disposal
```

