---
title: Bottomless Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.wZadGobkdXV95xbz" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Bottomless Pit"
level: "Hazard 9"


trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 20
sourcebook: "_Pathfinder GM Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +12, __Ref__ +12, "
hp: 36
health:
  - name: ""
  - name: "HP"
    desc: "36; __Hardness__ 9; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(or 0 if the trapdoor is disabled or broken) or _detect magic_"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An iron trapdoor covers an infinitely deep 10-foot-square pit."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (trained) to remove the trapdoor"
attacks:
  - name: ""

  - name: "Infinite Pitfall"
    desc: "`pf2:r` **Trigger** A creature walks onto the trapdoor\n* * *\n\n**Effect** The triggering creature falls in and continues to fall, potentially forever. That creature can try to [[Actions/Grab an Edge|Grab an Edge]] to avoid falling. The DC to Climb the walls or Grab an Edge is 26. The pit contains many handholds, so the falling creature can try to Grab an Edge again every 6 seconds. If the creature succeeds, it can start to Climb out from that point (though it might be a very long climb, depending on how far the creature fell). Since the creature falls endlessly, it can rest and even prepare spells while falling, though items dropped while falling are usually lost forever."


  - name: "Reset"
    desc: "The trap still causes creatures to fall forever if they fall in, but the trapdoor must be reset manually for the trap to become Hidden again."
```

```encounter-table
name: Bottomless Pit
creatures:
  - 1: Bottomless Pit
```

