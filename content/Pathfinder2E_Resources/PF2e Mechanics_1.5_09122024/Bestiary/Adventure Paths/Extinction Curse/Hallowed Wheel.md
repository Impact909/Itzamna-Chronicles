---
title: Hallowed Wheel
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #152: Legacy of the Lost God
aliases: "Actor.V9FUggmiabT6fmMW" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #152: Legacy of the Lost God"
name: "Hallowed Wheel"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 19
sourcebook: "_Pathfinder #152: Legacy of the Lost God_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +15, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Hardness__ 16; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(expert) to detect the magical sensor; noticing the wheel has a DC of 0"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An ornate wheel, divided into eight segments with a rune painted on each, is mounted on a pole and controlled by a lever that can be triggered manually or a sensor that detects creatures within 30 feet in front of it."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 31 Thievery check (master) on the wheel to flip the switch returning it to a harmless carnival game, DC 26 Thievery check (expert) to erase each rune, or [[Spells/Dispel Magic|Dispel Magic]] (5th level; counteract DC 28) to counteract each rune."
attacks:
  - name: ""

  - name: "Wheel Spin"
    desc: "`pf2:r` **Trigger** A creature pulls the lever or enters the sensor's detection area\n* * *\n\n**Effect** The wheel begins to spin and rolls initiative."

  - name: "Routine"
    desc: "(2 actions) On its initiative, the trap uses its first action to spin, then stops. Roll 1d8 to determine which segment is topmost when the wheel stops spinning. The wheel uses its second action to replicate the spell listed for that segment (5th level, DC 27, spell attack roll +17). This spell's target is centered on or otherwise includes the nearest creature in the spell's area. This increases the spell's range to 30 feet if necessary. Any spell cast by this trap is occult.\n\n1 - [[Spells/Black Tentacles|Black Tentacles]] 20-foot burst Spell Attack vs. Target's Fortitude DC\n\n2 - [[Spells/Blindness|Blindness]] DC 27 Fortitude check\n\n3 - [[Spells/Confusion|Confusion]] DC 27 Will check\n\n4 - [[Spells/Death Ward|Death Ward]] Range 30 feet\n\n5 - [[Spells/Outcast's Curse|Outcast's Curse]] DC 27 Will check Range 30 feet\n\n6 - [[Spells/Shadow Blast|Shadow Blast]] 30-foot line DC 27 Reflex check or DC 27 Will check 5d8 force damage\n\n7 - [[Spells/Noise Blast|Noise Blast]] 10-foot burst DC 27 Fortitude check 2d10 sonic damage\n\n8 - [[Spells/Gecko Grip|Gecko Grip]] Range 30 feet"
  - name: "Reset"
    desc: "The trap deactivates and resets if 1 minute passes without any creature moving within range of its sensor."
```

```encounter-table
name: Hallowed Wheel
creatures:
  - 1: Hallowed Wheel
```

