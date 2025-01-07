---
title: Poisonous Pollen Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.wChd613tkPRugzPP" 
level: 8
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Poisonous Pollen Trap"
level: "Hazard 8"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +13, "
hp: 62
health:
  - name: ""
  - name: "HP"
    desc: "62; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 28" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Flowers carved into the door emit colorful pollen when the door is touched."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (expert) to deface the flower carvings, DC 25 Nature check (expert) to neutralize the pollen, or [[Spells/Dispel Magic|Dispel Magic]] (4th rank; counteract DC 26) to counteract the conjuration"
attacks:
  - name: ""

  - name: "Pollinate"
    desc: "`pf2:r` (mental, poison, primal) **Trigger** The door is touched, or the lock is opened\n* * *\n\n**Effect** The flowers spray poisonous pollen in a 30-foot cone. A creature in the area must attempt a DC 24 Fortitude check save, with the following effect.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d10+11 poison damage and becomes [[Conditions/Enfeebled|Enfeebled 2]].\n\n**Failure** The creature takes 3d10+16 poison damage and 1d10 persistent poison damage, becomes enfeebled 2, and takes a –2 status penalty to Perception checks for 1d4 hours.\n\n**Critical Failure** The creature takes 4d10+22 poison damage and 1d10 persistent poison damage, becomes [[Conditions/Enfeebled|Enfeebled 4]], and takes a –2 status penalty to Perception checks and saves against poison for 24 hours."


  - name: "Reset"
    desc: "The trap resets after 1 hour."
```

```encounter-table
name: Poisonous Pollen Trap
creatures:
  - 1: Poisonous Pollen Trap
```

