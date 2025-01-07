---
title: Buzzing Latch Rune
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - electricity
  - magical
  - sonic
  - trap
  - pf2eHazard

source: Pathfinder #154: Siege of the Dinosaurs
aliases: "Actor.TVl0fFOBmNWDFtUB" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Buzzing Latch Rune"
level: "Hazard 13"


trait_01: [[electricity]]
trait_02: [[magical]]
trait_03: [[sonic]]
trait_04: [[trap]]
modifier: 22
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +19, "
hp: 84
health:
  - name: ""
  - name: "HP"
    desc: "84; __Hardness__ 21; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An invisible rune on the door begins emitting a very loud buzzing sound, potentially paralyzing an intruder."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 34 Thievery check (master) to disrupt the rune without triggering it or [[Spells/Dispel Magic|Dispel Magic]] (6th level; counteract DC 31) to magically counteract the rune"
attacks:
  - name: ""

  - name: "Jolting Buzz"
    desc: "`pf2:r` (electricity, primal, sonic) **Trigger** A creature attempts to open the door without using the key\n* * *\n\n**Effect** The trap makes a loud buzz and deals 5d10 electricity damage and 5d10 sonic damage to the triggering creature (DC 32 Reflex check save; this save applies to both the electricity damage and the sonic damage). Further, the creature must attempt a DC 32 Fortitude check save.\n* * *\n\n**Critical Success** No effect.\n\n**Success** The target is [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\n**Failure** The target is paralyzed for 1d4 rounds. At the end of each of its turns, it can attempt a new DC 32 Fortitude check save to reduce the remaining duration by 1 round, or end it entirely on a critical success.\n\n**Critical Failure** The target is paralyzed for 1 minute. At the end of each of its turns, it can attempt a new Fortitude save to reduce the remaining duration by 1 round, or end it entirely on a critical success."


  - name: "Reset"
    desc: "The trap resets after 1 hour."
```

```encounter-table
name: Buzzing Latch Rune
creatures:
  - 1: Buzzing Latch Rune
```

