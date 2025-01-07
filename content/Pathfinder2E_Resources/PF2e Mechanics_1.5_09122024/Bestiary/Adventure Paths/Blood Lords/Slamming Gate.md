---
title: Slamming Gate
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #181: Zombie Feast
aliases: "Actor.UgTNruhzmCoNL2Yn" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Slamming Gate"
level: "Hazard 1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +2, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20; __Hardness__ 5; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The heavy gate slams shut when opened more than halfway"
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 15 Thievery check (trained) to loosen the gate's springs before it slams closed"
attacks:
  - name: ""

  - name: "Slam Shut"
    desc: "`pf2:r` **Trigger** The door is opened more than halfway\n* * *\n\n**Effect** The door slams shut and deals 3d8 bludgeoning damage to any creature in the way (DC 17 Reflex check). On a critical failure, the creature is also [[Conditions/Restrained|Restrained]] by the closed door until it [[Actions/Escape|Escapes]] (DC 17)"


  - name: "Reset"
    desc: "The trap can be reactivated (or deactivated, if it's active) by flipping a lever hidden in the nearby wall. A character Searching the area finds it with a successful DC 18 Perception check check."
```

```encounter-table
name: Slamming Gate
creatures:
  - 1: Slamming Gate
```

