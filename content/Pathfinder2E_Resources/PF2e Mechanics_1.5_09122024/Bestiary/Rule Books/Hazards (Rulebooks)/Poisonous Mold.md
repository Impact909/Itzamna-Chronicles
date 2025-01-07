---
title: Poisonous Mold
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - fungus
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.kgT5ghGXSaaJxKto" 
level: 2
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Poisonous Mold"
level: "Hazard 2"


trait_01: [[environmental]]
trait_02: [[fungus]]
modifier: 11
sourcebook: "_Pathfinder GM Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 10"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "This grotesque fungus releases poisonous spores when a creature comes near."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Survival check (trained) to safely remove the mold"
attacks:
  - name: ""

  - name: "Feed on Decay"
    desc: "passive The mold expands when fed by blood or decay. If at any point a creature takes bleed damage while adjacent to the mold or a dying or dead body is adjacent to the mold, the mold grows to expand into every square adjacent to its current space. This can happen only once per day."

  - name: "Spore Burst"
    desc: "`pf2:r` (poison) **Frequency** once per day\n\n**Trigger** A creature touches the mold, hits it, or damages it\n* * *\n\n**Effect** The mold explodes in a burst of spores and mold clusters, dealing 2d6+6 poison damage to creatures within 10 feet of it, with a DC 18 Fortitude check save."

  - name: "Floating Spores"
    desc: "passive (aura, poison) 5 feet. A creature that enters or starts its turn in the aura takes 2d6 poison damage."


  - name: "Reset"
    desc: "Unless entirely eradicated (typically with acid or fire), the mold regrows over the course of 2 weeks."
```

```encounter-table
name: Poisonous Mold
creatures:
  - 1: Poisonous Mold
```

