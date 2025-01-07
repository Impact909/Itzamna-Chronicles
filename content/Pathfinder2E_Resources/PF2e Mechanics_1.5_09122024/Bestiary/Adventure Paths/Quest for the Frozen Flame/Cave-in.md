---
title: Cave-in
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

source: Pathfinder #176: Lost Mammoth Valley
aliases: "Actor.G32k0g5P8Dog92ys" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Cave-in"
level: "Hazard 4"


trait_01: [[environmental]]
modifier: 12
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +14, "
hp: 46
health:
  - name: ""
  - name: "HP"
    desc: "46; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 22" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The tunnel collapses, filling the passage with stone."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Survival check (trained) to prop up the tunnel ceiling without triggering a collapse"
attacks:
  - name: ""

  - name: "Collapse"
    desc: "`pf2:r` **Trigger** A creature moves into the unstable tunnel\n* * *\n\n**Effect** The tunnel collapses in a cave-in that deals 4d8+10 bludgeoning damage to the triggering creature and all creatures in area **A2** (DC 21 Reflex check). On a failed save, the triggering creature is [[Conditions/Immobilized|Immobilized]] (Escape DC 21). This collapse fully blocks the tunnel (area **A2**), making it impassable."



```

```encounter-table
name: Cave-in
creatures:
  - 1: Cave-in
```

