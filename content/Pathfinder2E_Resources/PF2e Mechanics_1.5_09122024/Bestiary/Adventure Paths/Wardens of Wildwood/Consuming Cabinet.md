---
title: Consuming Cabinet
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.qZeVFodhm7AGWOpP" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Consuming Cabinet"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 20
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +21, __Ref__ +15, "
hp: 70
health:
  - name: ""
  - name: "HP"
    desc: "70, Door Hardness 10; Door HP 40 (BT 20); __Hardness__ 16; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Animated cabinet imprisons intruders. The cabinet has two compartments; each can hold a single Medium creature or two Small-sized creatures or smaller."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Thievery check (expert) twice on cabinet; DC 28 Crafting check or DC 28 Thievery check (expert) to remove each or two doors"
attacks:
  - name: ""

  - name: "It's Alive!"
    desc: "`pf2:r` (attack) **Trigger** A living creature moves adjacent to the cabinet\n* * *\n\n**Effect** The cabinet animates and makes a door Strike against one adjacent creature. The hazard then rolls initiative."

  - name: "Capture"
    desc: "passive The target is trapped inside the cabinet's interior, gaining the [[Conditions/Grabbed|Grabbed]] condition until it [[Actions/Escape|Escapes]] (DC 32), another creature [[Actions/Force Open|Forces Open]] the cabinet door (DC 32), or that cabinet door is destroyed. Each of the two cabinet interiors can contain one Medium creature, or two Small-sized creatures or smaller."
  - name: "Melee"
    desc: "Door +21 () "

  - name: "Batter"
    desc: "action (attack) The cabinet shakes, dealing 2d10+13 bludgeoning damage to all creatures it has [[Conditions/Grabbed|Grabbed]]."

  - name: "Routine"
    desc: "(3 actions) The trap uses its first action to move directly toward the nearest living creature, its second action to make a door Strike against each adjacent creature, and its third action to Batter. This trap doesn't take a multiple attack penalty.\n* * *\n\n**Speed** 15 feet"
  - name: "Reset"
    desc: "The trap resets after 1 hour."
```

```encounter-table
name: Consuming Cabinet
creatures:
  - 1: Consuming Cabinet
```

