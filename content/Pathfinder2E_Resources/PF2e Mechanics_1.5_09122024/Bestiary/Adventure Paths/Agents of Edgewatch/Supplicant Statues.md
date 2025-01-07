---
title: Supplicant Statues
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #160: Assault on Hunting Lodge Seven
aliases: "Actor.mwFjhp2fkV7NAo7T" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Supplicant Statues"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
modifier: 30
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +20, __Ref__ +28, "
hp: 96
health:
  - name: ""
  - name: "HP"
    desc: "96, &lt;strong&gt;Control Panel Hardness&lt;/strong&gt; 10; &lt;strong&gt;Control Panel HP&lt;/strong&gt; 20 (BT 10); __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Six statues rapidly slide around the room on rollers, slowing down intruders and striking at them with spring-loaded sword arms."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 34 Thievery check (master) to disable a specific statue's rollers, or DC 39 Thievery check (master) on the control panel in **A4** deactivates the whole trap. For each statue disabled, the trap loses 1 action from its routine and the DC for its predictive impediment ability decreases by 4. [[Spells/Dispel Magic|Dispel Magic]] (7th level, counteract DC 32) doesn't harm the statues but removes the predictive impediment ability. Breaking the control panel prevents the trap from resetting."
attacks:
  - name: ""

  - name: "Animated Statues"
    desc: "`pf2:r` **Trigger** A creature enters a square adjacent to a statue\n* * *\n\n**Effect** The trap makes a statue shortsword Strike against the triggering creature, activates its predictive impediment ability, and then rolls initiative."

  - name: "Predictive Impediment"
    desc: "passive (arcane) The statues continually slide around to bump into creatures and block their passage through the room. The first time on its turn that a creature attempts to move within the room, it must succeed at a DC 36 Reflex check save or treat the entire room as difficult terrain for 1 round. On a critical failure, the creature is also knocked prone."
  - name: "Melee"
    desc: "Statue Shortsword +28 () "

  - name: "Routine"
    desc: "(6 actions) On the trap's initiative, each functioning statue slides up to 40 feet around the room and makes a statue shortsword Strike against an adjacent creature. The trap doesn't take a multiple attack penalty, and the statues' movements don't trigger reactions."
  - name: "Reset"
    desc: "The trap deactivates and resets one minute after the room is empty."
```

```encounter-table
name: Supplicant Statues
creatures:
  - 1: Supplicant Statues
```

