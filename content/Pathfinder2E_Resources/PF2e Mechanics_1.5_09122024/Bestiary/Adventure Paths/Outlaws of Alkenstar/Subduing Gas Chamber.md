---
title: Subduing Gas Chamber
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #178: Punks in a Powder Keg
aliases: "Actor.4YNtRFXjozbdeEP6" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Subduing Gas Chamber"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +15, __Ref__ +9, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(Expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A mechanical sensor in the desk drawer releases a counterweight in the wall, which slams the door shut and opens the sleeping gas tank under the bed, allowing gas to fill the air-tight room with a hissing sound."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (Trained) to disconnect the wire to the counterweight, preventing it from falling, or DC 20 Crafting check (Alchemical Crafting) to create a counteragent to the sleeping gas"
attacks:
  - name: ""

  - name: "Slam Door"
    desc: "`pf2:r` **Trigger** A creature opens the desk drawer without holding the release button under the desk\n* * *\n\n**Effect** The wooden door to the room slams shut and locks, and the trap rolls initiative."

  - name: "Sleeping Gas"
    desc: "passive (inhaled, poison) **Saving Throw** DC 22 Fortitude check\n\n**Maximum Duration** 4 hours\n\n**Stage 1** [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 2** [[Conditions/Unconscious|Unconscious]] with no Perception check to wake up (1 round)\n\n**Stage 3** unconscious with no Perception check to wake up (1 hour)"

  - name: "Routine"
    desc: "(1 action) Each round on its initiative count, the trap pumps more sleeping gas into the room. Any breathing creature in the room is exposed to the toxin. If a creature acts before the trap on the first round, it has the option of holding its breath to postpone breathing in the poison-holding one's breath after the trap's first action has no effect, since the air in the creature's lungs is already tainted. The trap functions for 1 minute before all the gas is expended, after which it rapidly decays over the next minute. Opening the door to an adjacent room cuts the remaining time it takes for the gas to decay in half but exposes creatures in that room as well."
  - name: "Reset"
    desc: "The gas must be manually reloaded."
```

```encounter-table
name: Subduing Gas Chamber
creatures:
  - 1: Subduing Gas Chamber
```

