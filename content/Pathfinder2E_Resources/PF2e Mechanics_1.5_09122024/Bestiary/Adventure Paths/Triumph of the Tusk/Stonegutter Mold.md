---
title: Stonegutter Mold
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - fungus
  - pf2eHazard

  - remaster
source: Pathfinder #207: The Resurrection Flood
aliases: "Actor.hb3JNbZ9V7qlcy5t" 
level: 7
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Stonegutter Mold"
level: "Hazard 7"


trait_01: [[environmental]]
trait_02: [[fungus]]
modifier: 17
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +19, __Ref__ +12, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 10"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A hardy, innocuous-looking green mold grows over surfaces, slowly absorbing minerals."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Survival check (trained) to scrape away the mold without touching it"
attacks:
  - name: ""

  - name: "Calcium Consumption"
    desc: "`pf2:r` **Trigger** A creature with bones touches the mold or steps into an area covered with it\n* * *\n\n**Effect** The mold shudders and slithers onto the triggering creature as it attempts to absorb calcium through their skin. The creature attempts a DC 25 Fortitude check save.\n* * *\n\n**Critical Success** The target shakes the mold off and is unaffected.\n\n**Success** A small patch of mold clings to the target and deals 2d10+9 piercing damage.\n\n**Failure** The mold clings to the target. The target takes 4d10+18 piercing damage and is [[Conditions/Drained|Drained 1]].\n\n**Critical Failure** The mold envelops the target. As failure, except the target is also [[Conditions/Slowed|Slowed 1]] until it's healed to its Hit Point maximum.\n\n_Note: A DC was not provided for this ability by Paizo. The DC present here is a hard DC for the hazard level according to the GM Core hazard building Tables._"


  - name: "Reset"
    desc: "1 hour, as the mold settles back across the surface."
```

```encounter-table
name: Stonegutter Mold
creatures:
  - 1: Stonegutter Mold
```

