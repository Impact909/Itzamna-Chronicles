---
title: Orb Blast Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.jhuSRy2PQAn9F4Je" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Orb Blast Trap"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 35
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +27, __Ref__ +33, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40, per orb; __Hardness__ 30; __Immunities__  object immunities,  critical hits,  precision; __Resistances__ slashing 15"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: "(master) to realize that the glimmering orbs signal a dangerous trap."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Five globes shoot bolts of force up and down the hall when a second creature reaches its midpoint."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Thievery check (master) to deactivate the trap entirely before it triggers, DC 45 Thievery check (expert) to deactivate one of the glimmering orbs after the trap rolls initiative, or [[Spells/Dispel Magic|Dispel Magic]] (9th level; counteract DC 41) to deactivate the trap entirely."
attacks:
  - name: ""

  - name: "Slam Doors"
    desc: "`pf2:r` (arcane) **Trigger** A second creature crosses a magical sensor at the midpoint of the hall.\n* * *\n\n**Effect** The doors at either end of the hall slam shut and lock in place while the trap is active (the doors open automatically if the trap is disabled or destroyed). The doors (Hardness 14, HP 56 [28 BT]) can be Forced Open with a DC 40 Athletics check check, or via a DC 35 Thievery check check to Pick the Lock. The trap rolls initiative."
  - name: "Melee"
    desc: "Force Bolt +35 () (can target any creature in area **A8**)"

  - name: "Routine"
    desc: "(5 actions) Five energized orbs each take one action to make a force bolt attack against a different target in the hallway (a single target cannot be fired at more than once per round by the trap). The trap doesn't take multiple attack penalties. Each orb that is disabled or destroyed reduces the trap's actions by 1."
  - name: "Reset"
    desc: "The trap deactivates 1 round after it has no creatures to target and resets automatically after 1 minute."
```

```encounter-table
name: Orb Blast Trap
creatures:
  - 1: Orb Blast Trap
```

