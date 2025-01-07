---
title: Flensing Floor
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Adventure: Prey for Death
aliases: "Actor.O27eIFtAHhLEfV9P" 
level: 18
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Flensing Floor"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 35
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +27, __Ref__ +33, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 30; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Long saw-toothed blades slash up along the [[Conditions/Hidden|Hidden]] grooves in the floor, their edges caked with what looks like blood but is in fact a deadly poison."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 45 Thievery check (master) once per weapon rack to detach the triggers from the trap mechanism"
attacks:
  - name: ""

  - name: "Sudden Blades"
    desc: "`pf2:r` **Trigger** Either of the weapons stored on either weapon rack is disturbed\n* * *\n\n**Effect** Both doors into this room slam shut and lock (DC 40). The trap then rolls initiative."
  - name: "Melee"
    desc: "Sawtooth Saber +32 () "

  - name: "Routine"
    desc: "(10 actions) The trap rolls a sawtooth saber Strike for each action, divided targets evenly among creatures in the trapped area. If there aren't enough targets in area **B7** to divide these actions evenly, additional targets are randomly chosen. The trap loses one action for each destroyed blade. The trap ignores multiple attack penalties."
  - name: "Reset"
    desc: "Manual."
```

```encounter-table
name: Flensing Floor
creatures:
  - 1: Flensing Floor
```

