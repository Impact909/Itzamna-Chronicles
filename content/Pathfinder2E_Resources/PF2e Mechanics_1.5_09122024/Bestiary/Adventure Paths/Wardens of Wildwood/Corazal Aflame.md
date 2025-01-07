---
title: Corazal Aflame
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - fire
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.HQiVwgAyJHySd3dZ" 
level: 10
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Corazal Aflame"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[fire]]
modifier: -10
sourcebook: "_Pathfinder #202: Severed at the Root_"
perception:
  - name: ""
  - name: "Stealth DC -10" 
    desc: " -10"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Fire burns Corazal and threatens to spread to the surrounding forest."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Nature check or DC 30 Survival check (expert) to douse flames or DC 32 Athletics check (expert) to smother flames; on the sixth successful check, the flames go out. Casting a non-cantrip water spell on the flames counts as one success."
attacks:
  - name: ""

  - name: "Blaze"
    desc: "`pf2:r` **Trigger** A living creature approaches Corazal\n* * *\n\n**Effect** The flames blaze higher, dealing 2d12+13 fire damage to the triggering creature (DC 29 Reflex check save). The hazard then rolls initiative."

  - name: "Routine"
    desc: "(1 action; fire) On its turn, the fire deals 2d8+13 fire damage to creatures in the grove, plus an additional 6 fire damage to Corazal and any creature within 15 feet of them (DC 29 Reflex check save)."

```

```encounter-table
name: Corazal Aflame
creatures:
  - 1: Corazal Aflame
```

