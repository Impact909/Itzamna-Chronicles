---
title: Time Rift
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #186: Ghost King&#x27;s Rage
aliases: "Actor.gPMK6RzYoi6kwbz0" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King's Rage"
name: "Time Rift"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 42
sourcebook: "_Pathfinder #186: Ghost King's Rage_"
perception:
  - name: ""
  - name: "Stealth DC 42" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A time rift focused on the sundial causes time to pass erratically for all creatures in the area."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three DC 48 Thievery check (legendary) or DC 48 Occultism check (master) checks to mend the time rift."
attacks:
  - name: ""

  - name: "Pause"
    desc: "`pf2:r` (incapacitation) **Trigger** A creature enters the area\n* * *\n\n**Effect** The triggering creature becomes temporarily unmoored from time, becoming [[Conditions/Stunned|Stunned 3]]. If the creature succeeds at a DC 47 Will check save, they reduce this to [[Conditions/Stunned|Stunned 1]]. The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) On its initiative, the time rift alters each creature's timeline. Each creature in the area rolls a 1d4 to randomly determine the effect on them.\n\n**1** The creature becomes [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**2** The creature is unaffected.\n\n**3** The creature is affected erratically by time; they're [[Conditions/Concealed|Concealed]] for 1 round.\n\n**4** The creature becomes [[Conditions/Quickened|Quickened]] 1 for 1 round."

```

```encounter-table
name: Time Rift
creatures:
  - 1: Time Rift
```

