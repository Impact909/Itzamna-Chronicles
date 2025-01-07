---
title: Ink Drowning Vats
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #161: Belly of the Black Whale
aliases: "Actor.IaG1rkc5zIiY2BIi" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Ink Drowning Vats"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[mechanical]]
modifier: 36
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +27, "
hp: 112
health:
  - name: ""
  - name: "HP"
    desc: "112; __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 36" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Steel hatch doors automatically lock shut in each of the four vats labeled **J2**. Four ink spouts (one per vat) jut through a narrow aperture in the ceiling of each vat, 20 feet above."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Thievery check (master) to seal an ink spout, DC 48 Thievery check (master) to unlock a steel hatch door, or DC 45 Athletics check (master) to Force Open a steel hatch door"
attacks:
  - name: ""

  - name: "Fill Tank"
    desc: "`pf2:r` **Trigger** The switch outside the vats is pulled\n* * *\n\n**Effect** The trap rolls initiative."

  - name: "Poison Ink"
    desc: "passive (poison) **Saving Throw** DC 38 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 3d6 poison damage and sickened 1 (1 round)\n\n**Stage 2** 4d6 poison damage and sickened 2 (1 round)"

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action for each disabled ink spout. On each of the trap's actions, a spout pours ink, increasing the depth of the ink in that vat by 2 feet. Creatures standing in the ink are exposed to a dose of poison ink. Once the vat is full of ink, the trap stops using actions, but creatures in the vat might start drowning."
  - name: "Reset"
    desc: "The trap can be reset by refilling the ink storage tanks above the vats."
```

```encounter-table
name: Ink Drowning Vats
creatures:
  - 1: Ink Drowning Vats
```

