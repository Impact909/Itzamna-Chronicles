---
title: Phantom Jailer
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard

source: Pathfinder Book of the Dead
aliases: "Actor.6ROiDxGTuu6AADI3" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Phantom Jailer"
level: "Hazard 3"


trait_01: [[haunt]]
modifier: 10
sourcebook: "_Pathfinder Book of the Dead_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(trained) to notice the manacles twitch"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A spirit appears and arrests the creature by clamping manacles around their wrists."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Athletics check to seize the manacles from the spirit, DC 19 Intimidation check (trained) to order the spirit to stand down, or DC 20 Occultism check to exorcise the spirit"
attacks:
  - name: ""

  - name: "Capture"
    desc: "`pf2:r` **Trigger** A creature touches the manacles\n* * *\n\n**Effect** The spirit attempts to lock the manacles around the triggering creature's wrists. The triggering creature must attempt a DC 23 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The spirit loosely places manacles around the creature's wrists. Removing the manacles requires a single action.\n\n**Failure** The spirit clamps the manacles around the creature's wrists but fails to lock them. The creature is [[Conditions/Off-Guard|Off-Guard]] and [[Conditions/Clumsy|Clumsy 1]] until the manacles are removed as a 3-action activity.\n\n**Critical Failure** The spirit clamps the manacles around the creature's wrists and locks them. The creature is off-guard and clumsy 1 until the manacles are removed ([[Actions/Escape|Escape]] DC 23, simple lock)."


  - name: "Reset"
    desc: "1 day"
```

```encounter-table
name: Phantom Jailer
creatures:
  - 1: Phantom Jailer
```

