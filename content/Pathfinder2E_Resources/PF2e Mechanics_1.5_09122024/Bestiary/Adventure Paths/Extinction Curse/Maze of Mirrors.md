---
title: Maze of Mirrors
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #152: Legacy of the Lost God
aliases: "Actor.psWcwTgYlldp6XEA" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #152: Legacy of the Lost God"
name: "Maze of Mirrors"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #152: Legacy of the Lost God_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +29, __Ref__ +14, "
hp: 64
health:
  - name: ""
  - name: "HP"
    desc: "64; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained) to detect the magical runes in the maze; noticing the maze itself has a DC of 0"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Invisible runes in the maze disorient those within it and cause its mirrored walls to shift about."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (expert) or [[Spells/Dispel Magic|Dispel Magic]] (5th level; counteract DC 28) to stop the mirrors' shuffling; DC 28 Occultism check or DC 28 Religion check (expert) to dispel the minotaur"
attacks:
  - name: ""

  - name: "The Maze Awakens"
    desc: "`pf2:r` **Trigger** A creature enters the maze\n* * *\n\n**Effect** Creatures in the maze can't escape it except by use of teleportation magic or as described in Trapped in the Maze. The trap rolls initiative."

  - name: "Trapped in the Maze"
    desc: "passive Once each turn after it has taken a move action within the maze, each target in the maze can spend 1 action to attempt a DC 26 Perception check or DC 26 Survival check check to escape it. A group traveling the maze together is treated as a single target; no more than one creature in the group can attempt this check each round, but accompanying creatures can Aid this check. The possible outcomes follow. A target attempting to leave the maze the same way it entered uses the outcome for one degree of success better than the result of its roll when attempting this check (failure to success, for example).\n* * *\n\n**Critical Success** The target escapes the maze.\n\n**Success** The target is on the right path to the exit. If the target was already on the right path, it escapes the maze.\n\n**Failure** The target makes no progress toward escape.\n\n**Critical Failure** The target makes no progress toward escape, and if it was on the right path, it no longer is."
  - name: "Melee"
    desc: "Spectral Gore +21 () "

  - name: "Routine"
    desc: "(3 actions) The trap uses its first action to magically shuffle the mirrors, rendering markings or maps of the maze ineffective. Creatures in the maze that fail a DC 26 Will check save are [[Conditions/Stupefied|Stupefied 1]] until they leave the maze. If the target fails additional saves against this ability, the condition value increases by 1 (to a maximum of [[Conditions/Stupefied|Stupefied 4]]).\n\nFor its second action, the trap's ghostly minotaur attacks a random creature in the maze with its spectral gore.\n\nFor its third action, the trap makes another spectral gore attack against a random creature."
  - name: "Reset"
    desc: "The trap deactivates and resets if 1 minute passes without any creature in the maze."
```

```encounter-table
name: Maze of Mirrors
creatures:
  - 1: Maze of Mirrors
```

