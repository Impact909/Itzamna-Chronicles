---
title: Stonescale Spirits
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #163: Ruins of Gauntlight
aliases: "Actor.7n9vfR53f8RJNrnz" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Stonescale Spirits"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 11
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A half-dozen ghostly kobolds rise from the rubble in a howling vortex."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Intimidation check (trained) to frighten the spirits with a threatening display, or DC 21 Religion check (trained) to exorcise the spirits"
attacks:
  - name: ""

  - name: "Confusing Confrontation"
    desc: "`pf2:r` (emotion, fear, mental) **Trigger** A creature enters a square either fully or partially filled with rubble in the middle of the room\n* * *\n\n**Effect** Six ghostly kobolds surge out of the rubble with eerie yowls. Each creature in area **A7** must attempt a DC 18 Will check save with the following results. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected, is temporarily immune to Confusing Confrontation for 24 hours, and realizes that a display of intimidating dominance might quell the ghostly kobolds' assault.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Confused|Confused]] for 1 round and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Confused|Confused]] for 2 rounds and is [[Conditions/Frightened|Frightened 3]]."

  - name: "Routine"
    desc: "(1 action) The spirits swoop together toward one creature in area **A7** who's [[Conditions/Frightened|Frightened]], instilling feelings of betrayal and confusion. The target takes 1d10+4 mental damage (DC 18 Will check save)."
  - name: "Reset"
    desc: "The haunt deactivates if there are no frightened creatures in area **A7** at the start of its turn. The ghostly kobolds return to the rubble pile.\n\nThe haunt can't activate again for 1 hour."
```

```encounter-table
name: Stonescale Spirits
creatures:
  - 1: Stonescale Spirits
```

