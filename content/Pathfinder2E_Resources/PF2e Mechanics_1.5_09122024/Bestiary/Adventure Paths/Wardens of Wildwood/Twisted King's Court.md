---
title: Twisted King's Court
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - magical
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #203: Shepherd of Decay
aliases: "Actor.9wtkwPbgNulDJGQL" 
level: 12
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Twisted King's Court"
level: "Hazard 12"

trait_06: "Complex"
trait_01: [[haunt]]
trait_02: [[magical]]
modifier: 20
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Countless fey with grisly visages and misshapen bodies cavort throughout the room, kicking up caustic debris and pulling other creatures into their dangerous dance."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Nature check or DC 32 Occultism check (expert) to perform a ritual to ward the area against fey intrusion, DC 34 Performance check (master) to meet the Twisted King's demands with a disturbing dance, or DC 32 Athletics check or DC 32 Intimidation check (expert) to fend off or frighten the fey dancers. Three total successes are required to disable the haunt, and each check takes 2 actions."
attacks:
  - name: ""

  - name: "Welcome to the Feywrithe"
    desc: "`pf2:r` **Trigger** 1 round passes since both isqulugs in area **B6** are slain, or 10 rounds pass since they rolled initiative\n* * *\n\n**Effect** The isqulugs die horribly (if they're still alive), rent by clawed fey hands. Spectral fey pull at the other creatures in the caves, all of which must attempt a DC 36 Fortitude check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is pulled 10 feet toward the standing stones.\n\n**Failure** The creature is pulled 15 feet toward the standing stones.\n\n**Critical Failure** The creature is pulled 15 feet toward the standing stones, knocked [[Conditions/Prone|Prone]], and takes 1d6 bludgeoning damage (in addition to any damage from the toxic water)."

  - name: "Routine"
    desc: "(1 action) Spectral fey cavort about the room. All creatures in the room are raked by ghostly claws and splashed with toxic water, taking 1d10+14 force + 2d10 acid damage (DC 32 Reflex check save). Creatures that critically fail their Reflex saves are pulled 10 feet toward the standing stones."
  - name: "Reset"
    desc: "The haunt deactivates after 1 minute. It re-forms every new moon. If all of the glyphs in area **B6** are restored—a process requiring 10 days of downtime and 10 successful DC 36 Nature check or DC 36 Occultism check checks—the haunt becomes permanently disabled and doesn't re-form."
```

```encounter-table
name: Twisted King's Court
creatures:
  - 1: Twisted King's Court
```

