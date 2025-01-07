---
obsidianUIMode: preview
title: "Petrify"
noteType: pf2eSpell
cssclasses: pf2e,pf2e-spell
tags:
  - pf2eSpell
  - spell/level/6
  - trait/concentrate
  - trait/earth
  - trait/manipulate
  - trait/common
  - tradition/arcane
  - tradition/primal

  - remaster
aliases: "Item.WQG94MyFI8FrQzcP" 
license: ORC
---
```statblock
name: "Petrify  `pf2:2`"
level: "Spell 6"

trait_01: [[concentrate]]
trait_02: [[earth]]
trait_03: [[manipulate]]
layout: Basic Pathfinder 2e Layout
columns: 1
columnWidth: x
abilities_top:
  - name: ""
  - name: "Traditions"
    desc: "arcane, primal"
  - name: "Range"
    desc: "120 feet; **Targets** 1 creature made of organic material"
  - name: "Defense"
    desc: " fortitude"
  - name: "Duration"
    desc: "varies"
abilities_mid:
  - name: ""
    desc: "The target's body slowly turns into a stone statue. The target must attempt a Fortitude save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Slowed|Slowed 1]] for 1 round as stone begins to form on their body.\n\n**Failure** The target is slowed 1 and must attempt a Fortitude save at the end of each of its turns; this ongoing save has the incapacitation trait. On a failed save, the slowed condition increases by 1 (or 2 on a critical failure) as stone growths creep across their body. A successful save reduces the slowed condition by 1. When a creature becomes fully unable to act due to the slowed condition from _petrify_, the spell then ends in a flash of gray light, leaving the target [[Conditions/Petrified|Petrified]] permanently as they become a statue. The spell also ends if the slowed condition is removed, which causes the stone to break off harmlessly.\n\n**Critical Failure** As failure, but the target is initially [[Conditions/Slowed|Slowed 2]]."
sourcebook: "_Pathfinder Player Core_"
```