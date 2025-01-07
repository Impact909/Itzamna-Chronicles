---
title: Occult Weather
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - haunt
  - occult
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #208: Hoof, Cinder, and Storm
aliases: "Actor.ujLIxfLN7pqgGgUX" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Occult Weather"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[haunt]]
trait_03: [[occult]]
modifier: 20
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert) or [[Spells/Detect Magic|Detect Magic]]."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The sky suddenly darkens with storm clouds rumbling overhead, the faces of the dead forming in the clouds above as their voices wail along the high winds."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Occultism check (expert) to funnel the magic powering the weather back into itself, or DC 30 Religion check (expert) to exorcise some of the trapped souls and weaken the storm; three total successes in any combination are required to disable the haunt"
attacks:
  - name: ""

  - name: "Thunder of Cries"
    desc: "`pf2:r` (auditory, sonic) **Trigger** A creature enters the haunt's area\n* * *\n\n**Effect** The clouds darken and thunder roars, filled with the wails and screams of those killed in these lands. The shrieks of the spirits deal 3d6+13 sonic damage to all creatures in the area (DC 28 Fortitude check save). The haunt then rolls initiative."

  - name: "Wind of Screams"
    desc: "action The occult weather intensifies the wind blowing around the area, buffeting all creatures within a 60-foot line. Each creature in the line must attempt a DC 32 Fortitude check save or be knocked [[Conditions/Prone|Prone]], taking 1d10+6 bludgeoning damage."
  - name: "Melee"
    desc: "Lightning +21 (electricity, range increment 60 feet) "

  - name: "Routine"
    desc: "(4 actions) The occult weather intensifies, with winds picking up speed and lightning and thunder sounding overhead. The occult weather uses 3 actions to make lightning Strikes against three random creatures, favoring orcs or anyone who attempted to Disable it within the past round, then uses Wind of Screams as its final action."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all creatures leave the Shadefields but resets immediately. The occult weather resets 1 day after being disabled if the ancestor storm isn't put to rest."
```

```encounter-table
name: Occult Weather
creatures:
  - 1: Occult Weather
```

