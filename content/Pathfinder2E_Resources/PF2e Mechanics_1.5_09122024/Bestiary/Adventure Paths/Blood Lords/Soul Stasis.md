---
title: Soul Stasis
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #186: Ghost King&#x27;s Rage
aliases: "Actor.tbyDC0L04E0PmJqa" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King's Rage"
name: "Soul Stasis"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 33
sourcebook: "_Pathfinder #186: Ghost King's Rage_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, "
hp: 114
health:
  - name: ""
  - name: "HP"
    desc: "114, Per pillar; __Hardness__ 29; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four steel pillars emit pulsing energy to slow souls' processes."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Arcana check or Religion (master) to reweave the magic within each pillar, DC 46 Thievery check (master) to disable each pillar, or dispel magic (8th level; counteract DC 43) to counteract each pillar"
attacks:
  - name: ""

  - name: "Pulse"
    desc: "`pf2:r` (divine) **Trigger** A soul or creature with a soul enters the area\n* * *\n\n**Effect** The steel pillars activate with an audible hum that resonates with spirits. Each non-psychopomp creature with a soul is [[Conditions/Stunned|Stunned 3]] unless they succeed at a DC 43 Will check save. The trap then rolls initiative."

  - name: "Routine"
    desc: "(4 actions) This trap loses 1 action each turn for each disabled pillar. Each pillar uses 1 action to emit a 30-foot-radius burst of inhibiting energy that slows souls. Each non-psychopomp creature with a soul in the area is [[Conditions/Slowed|Slowed 1]] unless they succeed at a DC 43 Fortitude check save."
  - name: "Reset"
    desc: "The trap deactivates and resets if 1 minute passes without any souls in the area."
```

```encounter-table
name: Soul Stasis
creatures:
  - 1: Soul Stasis
```

