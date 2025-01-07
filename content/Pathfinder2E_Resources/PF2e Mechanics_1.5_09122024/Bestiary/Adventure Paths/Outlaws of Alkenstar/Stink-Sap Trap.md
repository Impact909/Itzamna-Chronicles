---
title: Stink-Sap Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #178: Punks in a Powder Keg
aliases: "Actor.U5eTbs9YE3ZAj1FA" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Stink-Sap Trap"
level: "Hazard 3"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +8, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A nozzle attached to a pressure sensor under the flagstone path sprays thick wads of smelly sap."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 15 Thievery check (trained) to clog the nozzle or DC 14 Athletics check (trained) to redirect the stream away from the path; the Athletics check can be made at a distance with a thrown object, but a critical failure triggers the trap's Sudden Spray."
attacks:
  - name: ""

  - name: "Sudden Spray"
    desc: "`pf2:r` **Trigger** A creature or object weighing at least 50 pounds is placed on one of the flagstones north of the gate (marked \"T\" on the map)\n* * *\n\n**Effect** Pressurized sap sprays from the nozzle, coating everything in a 15-foot cone. Creatures in the area that fail a DC 20 Reflex check save become affected by stink sap."

  - name: "Stink Sap"
    desc: "passive (aura, olfactory) 5 feet. Creatures and their equipment coated in the sap smell horrible. Creatures in the aura must attempt a DC 16 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, the creature is also [[Conditions/Stunned|Stunned 1]]. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is immune to stink sap for 1 minute. Creatures don't save against this effect in exploration mode and don't become temporarily immune, but creatures with stink sap on them must roll against their own aura when they roll initiative in encounter mode. The sap dissipates after 10 hours; spending 10 minutes scrubbing the sap off with soap and water reduces the duration by 1 hour.\n\n[[Bestiary Effects/Effect_ Stink Sap|Effect: Stink Sap]]"


  - name: "Reset"
    desc: "1 minute. The trap resets automatically twice before the supply of stink sap is exhausted."
```

```encounter-table
name: Stink-Sap Trap
creatures:
  - 1: Stink-Sap Trap
```

