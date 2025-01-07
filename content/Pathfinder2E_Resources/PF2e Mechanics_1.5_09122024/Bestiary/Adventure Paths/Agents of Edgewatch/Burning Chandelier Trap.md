---
title: Burning Chandelier Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #160: Assault on Hunting Lodge Seven
aliases: "Actor.Q5JGjKiqUcKA7HSN" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Burning Chandelier Trap"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
modifier: 26
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +22, "
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120, &lt;strong&gt;Panel Hardness&lt;/strong&gt; 18; &lt;strong&gt;Panel HP&lt;/strong&gt; 88 (BT 44); &lt;strong&gt;Resistances&lt;/strong&gt; cold 15; __Hardness__ 30; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 26" 
    desc: "(master) or DC 38 Perception check (master) to spot the trap's control panel"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four large flaming chandeliers swing wildly around the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 36 Thievery check (master) to disable a chandelier or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 33) to permanently drain the magic from a chandelier. Any amount of cold damage that overcomes a chandelier's cold resistance extinguishes its flames and removes its persistent fire damage and flame dart attack. DC 41 Thievery check (legendary) to disable the entire trap from the hidden control panel in the southeast corner of the room."
attacks:
  - name: ""

  - name: "Extending Chandeliers"
    desc: "`pf2:r` (occult) **Trigger** A creature touches the cage door, the closet door, or any wooden stand\n* * *\n\n**Effect** Both double doors leading out of the room shut and lock; while the trap is active, the key doesn't work to open these doors (although their locks can be picked normally). The chandeliers drop several feet on elongated chains, allowing them to swing around the room. The closest chandelier to the triggering creature makes a swinging chandelier Strike against it. The trap then rolls initiative."
  - name: "Melee"
    desc: "Swinging Chandelier +35 () "
  - name: "Melee"
    desc: "Flame Dart +32 (range increment 40 feet) "

  - name: "Routine"
    desc: "(4 actions) For every chandelier disabled, the trap's actions are reduced by 1. For each of the trap's actions, a different chandelier attacks a random creature in the room. A chandelier uses its swinging chandelier attack if it can, but it can't make melee attacks against creatures in the cage, the closet, or the gap between the two double doors leading into the vault. Against a creature it can't reach with a melee attack, it uses a flame dart attack instead. The trap doesn't take multiple attack penalties."
  - name: "Reset"
    desc: "The trap deactivates and resets 1 minute after there are no living creatures remaining in the room."
```

```encounter-table
name: Burning Chandelier Trap
creatures:
  - 1: Burning Chandelier Trap
```

