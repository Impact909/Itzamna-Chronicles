---
title: Poisoned Lock (Lionlodge)
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder One-Shot #2: Dinner at Lionlodge
aliases: "Actor.z4f3JbaplJpWcPQs" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder One-Shot #2: Dinner at Lionlodge"
name: "Poisoned Lock (Lionlodge)"
level: "Hazard 5"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder One-Shot #2: Dinner at Lionlodge_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +15, __Ref__ +9, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 12; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A spring-loaded, poisoned needle is hidden near the drawer's keyhole. Disabling or breaking the trap does not disable or break the lock."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Thievery check (expert) on the spring mechanism."
attacks:
  - name: ""

  - name: "Spring"
    desc: "`pf2:r` **Trigger** A creature tries to unlock or [[Actions/Pick a Lock|Pick the Lock]]\n* * *\n\n**Effect** The needle extends to attack the triggering creature."
  - name: "Melee"
    desc: "Needle +19 () plus Enhanced Hunting Spider Venom"

  - name: "Enhanced Hunting Spider Venom"
    desc: "passive (poison) **Saving Throw** DC 23 Fortitude check\n\n**Maximum Duration** 6 rounds\n* * *\n\n**Stage 1** 1d10 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d12 poison damage, [[Conditions/Clumsy|Clumsy 1]], and off-guard (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and off-guard (1 round).\n* * *\n\n**Note** The clumsy condition caused by this venom persists for 24 hours before fading."



```

```encounter-table
name: Poisoned Lock (Lionlodge)
creatures:
  - 1: Poisoned Lock (Lionlodge)
```

