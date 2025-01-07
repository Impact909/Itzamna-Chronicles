---
title: "Arboreal Sapling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5L0d78JhgxVHKGDl" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Arboreal Sapling"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Arboreal Sapling"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[plant]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Low-Light Vision"
languages: "Arboreal, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Nature: +5, Stealth: +6"
abilityMods: [4, 0, 3, 0, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +6, __Will__ +9"
hp: 35
health:
  - name: ""
  - name: HP
    desc: "35; __Weaknesses__ axe vulnerability 5, fire 5; __Resistances__ bludgeoning 3, piercing 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Axe Vulnerability"
    desc: "  An arboreal sapling takes 5 additional damage from axes."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 ()\n__Damage__  1d10 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Branch"
    desc: "+10 (reach 10 feet)\n__Damage__  1d8 + 4 piercing"

  - name: "Shaky Footing"
    desc: "  When an arboreal sapling critically fails an attack roll or Reflex saving throw, it becomes [[Conditions/Prone|Prone]] unless it succeeds at a DC 11 Flat check."

  - name: "Timber!"
    desc: "`pf2:r`  **Trigger** An arboreal sapling that is not [[Conditions/Prone|Prone]] either becomes prone or is reduced to 0 HP\n* * *\n\n**Effect** The arboreal sapling topples over, dealing 2d6 bludgeoning damage to itself and to creatures in a 10-foot line (DC 16 Reflex check). Creatures that critically fail the saving throw are also knocked prone."
 
```

```encounter-table
name: Arboreal Sapling
creatures:
  - 1: Arboreal Sapling
```



Young arboreals often appear lanky and uncoordinated. Their awkwardness belies their burgeoning strength and decades of natural studies.

* * *

An arboreal's abilities gradually change as it grows, explores, and fulfills its forest's needs. After decades of life as an unremarkable tree, an arboreal sapling uproots itself to discover its greater purpose, often guided by elders.

## Always Growing

An arboreal sapling gradually grows into a more powerful form, such as an arboreal warden, filling whatever niche suits its interests and environment. However, even centuries later, an arboreal can slowly reshape itself to fill a new role, such as a warden transforming into an arboreal regent after their predecessor's retirement.

## Occult Nutrients

While drawing water, nutrients, and trace primal energy from the soil, an arboreal sometimes absorbs psychic impressions that shape its growth. Taking root in haunted landscapes or abandoned fairgrounds can result in truly sinister or frolicsome arboreals.
