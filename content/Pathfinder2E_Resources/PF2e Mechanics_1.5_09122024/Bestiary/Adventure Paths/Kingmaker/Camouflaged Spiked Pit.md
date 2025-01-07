---
title: Camouflaged Spiked Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.XYx9IvxrDd5FZ5pm" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Camouflaged Spiked Pit"
level: "Hazard 8"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 21
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC 31" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 20-foot deep, funnel-shaped pit with dozens of wooden spikes lining its walls."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Yanking the cloth away is a simple way to expose the danger to allow someone to merely avoid it by walking around its edges, but it cannot be quickly disabled."
attacks:
  - name: ""

  - name: "Spiked Pitfall"
    desc: "`pf2:r` **Trigger** A creature walks onto one of the pits\n* * *\n\n**Effect** The triggering creature falls and rolls through several spikes as it slides to the bottom. This inflicts 5 bludgeoning damage from the fall itself down the steep slope (the falling PC can't attempt to [[Actions/Grab an Edge|Grab an Edge]] due to the lack of defined edges to the pit's walls), but the falling PC must also attempt a DC 26 Reflex check save.\n* * *\n\n**Critical Success** The character avoids all of the spikes and takes no additional damage.\n\n**Success** The character takes 2d10+11 piercing damage from the spikes.\n\n**Failure** The character takes 4d10+22 piercing damage from the spikes.\n\n**Critical Failure** The character takes 4d10+22 piercing damage from the spikes plus 2d6 bleed damage. While the character is taking this bleed damage, they are also [[Conditions/Sickened|Sickened 2]] from the pain."


  - name: "Reset"
    desc: "Creatures can still fall into the trap once it has been exposed, but the camouflaged cover must be reset manually for the trap to become hidden again."
```

```encounter-table
name: Camouflaged Spiked Pit
creatures:
  - 1: Camouflaged Spiked Pit
```

