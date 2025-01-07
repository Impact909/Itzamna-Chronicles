---
title: Falling Debris
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: The Fall of Plaguestone
aliases: "Actor.fcEufehiR9CKCIqY" 
level: 1
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Falling Debris"
level: "Hazard 1"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +8, __Ref__ +2, "
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
    desc: "A pressure-sensitive floorboard connects to a beam holding up debris in the crawlway's ceiling."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 15 Thievery check (trained) on the floorboard before the debris falls"
attacks:
  - name: ""

  - name: "Falling Debris"
    desc: "`pf2:r` **Trigger** Pressure is placed on the floorboard.\n* * *\n\n**Effect** The ceiling in the crawlway collapses in the square where the passage turns, and also in the two adjacent squares. Anyone in these three squares takes 3d6 bludgeoning damage and can attempt a DC 14 Reflex check save to reduce the damage. For the creature in the center square, where the trap is triggered, this is a basic save. Creatures in the two adjacent squares take no damage on a success or critical success as they avoid the falling debris entirely, but take full damage on a failed save, and take double damage on a critical failure. Creatures that take damage from the debris are [[Conditions/Immobilized|Immobilized]], trapped under the crushing weight.\n\nClearing out a square of debris requires a successful DC 17 Athletics check skill check, with the following effects.\n* * *\n\n**Critical Success** The square is cleared in 1 minute.\n\n**Success** The square is cleared in 5 minutes.\n\n**Failure** The square is cleared in 10 minutes.\n\n**Critical Failure** The ceiling above the square collapses further, dealing an additional 2d6 bludgeoning damage to the character digging out the square and any character trapped in that square. This takes 1 minute and no progress is made."



```

```encounter-table
name: Falling Debris
creatures:
  - 1: Falling Debris
```

