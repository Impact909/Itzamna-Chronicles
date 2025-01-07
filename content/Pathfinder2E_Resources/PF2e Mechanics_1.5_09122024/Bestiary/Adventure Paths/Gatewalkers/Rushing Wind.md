---
title: Rushing Wind
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #187: The Seventh Arch
aliases: "Actor.z8gAMeNfbDqjB51f" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Rushing Wind"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 7
sourcebook: "_Pathfinder #187: The Seventh Arch_"
perception:
  - name: ""
  - name: "Stealth DC 7" 
    desc: "(trained) to detect the change in pressure"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A raging wind sucks creatures in the area toward the aiudara."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Thievery check (trained) or Arcana (trained) to recognize what's happening and craft a patch to block air from escaping through the portal"
attacks:
  - name: ""

  - name: "Gale"
    desc: "`pf2:r` **Trigger** The aiudara appears here on Eox\n* * *\n\n**Effect** A jet of wind pulls creatures caught between the worlds toward the archway. The hazard rolls initiative."

  - name: "Routine"
    desc: "(1 action) The hazard uses its action to suck each creature (except the cairn wight) toward the aiudara. Each affected creature must attempt a DC 18 Fortitude check save.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is pulled 5 feet toward the aiudara and is [[Conditions/Stunned|Stunned 1]]. If the creature is already adjacent to the aiudara, it doesn't move but is [[Conditions/Stunned|Stunned 2]].\n\n**Critical Failure** The creature is pulled 10 feet toward the aiudara, falls [[Conditions/Prone|Prone]], and is stunned 1. If the creature is already adjacent to the aiudara, it doesn't move but falls prone and is stunned 2."

```

```encounter-table
name: Rushing Wind
creatures:
  - 1: Rushing Wind
```

