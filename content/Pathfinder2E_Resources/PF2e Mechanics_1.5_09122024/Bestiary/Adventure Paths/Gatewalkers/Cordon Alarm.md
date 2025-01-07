---
title: Cordon Alarm
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #187: The Seventh Arch
aliases: "Actor.ILEYOVdIxpodIswy" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Cordon Alarm"
level: "Hazard 2"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder #187: The Seventh Arch_"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A hempen rope tied between trees emanates an [[Conditions/Invisible|Invisible]], cylindrical barrier that sounds an alarm when crossed."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to move the rope without setting of the alarm, or [[Spells/Dispel Magic|Dispel Magic]] (1st level; counteract DC 16) to disable the rope's magic"
attacks:
  - name: ""

  - name: "Alarm"
    desc: "`pf2:r` (primal) **Trigger** An object or creature of at least 1 Bulk crosses an invisible vertical barrier extending 30 feet above and below the rope\n* * *\n\n**Effect** The rope squawks like an angry squirrel from the point where the barrier was breached. This alarm is as loud as a human scream and lasts for 1 minute. If an item or creature is still breaching the barrier at the end of this duration, the alarm immediately triggers again."


  - name: "Reset"
    desc: "The alarm resets immediately. Multiple breaches can cause the alarm to sound in multiple places at the same time, though the alarm can still be triggered only once per round."
```

```encounter-table
name: Cordon Alarm
creatures:
  - 1: Cordon Alarm
```

