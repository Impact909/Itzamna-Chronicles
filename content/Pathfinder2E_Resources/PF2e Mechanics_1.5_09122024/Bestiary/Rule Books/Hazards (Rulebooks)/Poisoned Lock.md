---
title: Poisoned Lock
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.I4LEjjsHWFPDiDCt" 
level: 1
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Poisoned Lock"
level: "Hazard 1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder GM Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +4, "
hp: 24
health:
  - name: ""
  - name: "HP"
    desc: "24; __Hardness__ 6; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A spring-loaded, poisoned spine is hidden near the keyhole of a lock. Disabling or breaking the trap does not disable or break the lock."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 17 Thievery check (trained) on the spring mechanism"
attacks:
  - name: ""

  - name: "Spring"
    desc: "`pf2:r` (attack) **Trigger** A creature tries to unlock or Pick the Lock.\n* * *\n\n**Effect** A spine extends to Strike the triggering creature."
  - name: "Melee"
    desc: "Spine +13 () "

  - name: "Cladis Poison"
    desc: "passive (poison) **Saving Throw** DC 19 Fortitude check\n\n**Maximum Duration** 4 hours\n\n**Stage 1** 1d6 poison damage and [[Conditions/Drained|Drained 1]] (1 hour)\n\n**Stage 2** 2d6 poison damage and [[Conditions/Drained|Drained 2]] (1 hour)\n\n**Stage 3** 3d6 poison damage and drained 2 (1 hour)"



```

```encounter-table
name: Poisoned Lock
creatures:
  - 1: Poisoned Lock
```

