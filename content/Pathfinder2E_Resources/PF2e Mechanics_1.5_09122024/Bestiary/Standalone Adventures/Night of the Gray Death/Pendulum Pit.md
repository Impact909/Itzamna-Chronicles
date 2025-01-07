---
title: Pendulum Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Night of the Gray Death
aliases: "Actor.QhxMrOGQUvQZ1Ju8" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Pendulum Pit"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 36
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 36" 
    desc: "(legendary) to realize the chamber is a complex rotating trap before it triggers. No check is necessary to notice the platforms and the pit."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Several swinging pendulums of force cleave through the room across the platforms, knocking people into the pit."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Arcana check (legendary), DC 44 Thievery check (master), or [[Spells/Dispel Magic|Dispel Magic]] (9th level; counteract DC 44) on a platform to deactivate its pendulum blade; once all five platforms have been deactivated, the trap is disabled and the room rotates back into position along the exits. DC 48 Thievery check (legendary) from any blocked exit to activate the rotating mechanism and rotate the room back into position before the trap has been disabled."
attacks:
  - name: ""

  - name: "Locking Room"
    desc: "`pf2:r` **Trigger** A creature disturbs any of the platforms, or anything falls into the pit\n* * *\n\n**Effect** The room rotates 45 degrees, closing off the room by shifting its exits to face bare walls. A pendulum of force swings across the platform with the armor on it, knocking the armor into the pit and making a pendulum blade Strike against a creature on that platform (if any). The trap then rolls for initiative."
  - name: "Melee"
    desc: "Pendulum Blade +38 (fatal d12, force, magical) No MAP applies to strikes made by pendulum blade attacks"

  - name: "Pendulum Shove"
    desc: "passive A creature hit by a pendulum blade must succeed at a DC 44 Reflex check save or be moved 5 feet along the line of the pendulum's swing. This is forced movement."

  - name: "No MAP"
    desc: "passive The Pendulum Blade is unaffected by Multiple Attack Penalty"

  - name: "Routine"
    desc: "(5 actions) For each active platform, the trap uses an action to create a pendulum of force to swing down along a straight line between the platform and one other creature in the room that isn't on the platform (if any). The trap makes a pendulum blade attack against any creature in that line. For each platform deactivated, reduce the number of actions the trap takes in its routine by 1."
  - name: "Reset"
    desc: "The trap resets after 1 hour. If the [[Spells/Darkness|Darkness]] throughout the room has been dispelled, the _darkness_ in the room returns when the trap resets."
```

```encounter-table
name: Pendulum Pit
creatures:
  - 1: Pendulum Pit
```

