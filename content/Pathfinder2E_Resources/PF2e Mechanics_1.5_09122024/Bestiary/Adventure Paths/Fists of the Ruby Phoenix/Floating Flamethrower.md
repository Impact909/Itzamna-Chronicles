---
title: Floating Flamethrower
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - fire
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #167: Ready? Fight!
aliases: "Actor.pBcM6ypkc3UgVlko" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Floating Flamethrower"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[fire]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 23
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +30, __Ref__ +33, "
hp: 100
health:
  - name: ""
  - name: "HP"
    desc: "100; __Hardness__ 25; __Immunities__  object immunities,  fire; __Weaknesses__ cold 15"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "+23 (expert) or DC 38 Perception check (master) to notice the pattern of the orb's trajectory"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A floating skull of fire swoops around the arena, rotating as it weaves through the ring and releasing huge gouts of flame in random directions."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "three DC 40 Thievery check (legendary) checks or castings of [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 40), one each to pull out or disable the elemental cores hidden in the floating skull's right eye, left eye, and mouth"
attacks:
  - name: ""

  - name: "Blaze"
    desc: "`pf2:r` (fire) **Trigger** Hao Jin signals the start of the bout\n* * *\n\n**Effect** The trap roars with fire and rolls initiative."

  - name: "Speed Fly 50 feet"
    desc: "passive "

  - name: "Routine"
    desc: "(3 actions) The trap loses 1 action per turn per successful check to disable. The floating flamethrower uses its first action to release a gout of flame in a 15-foot cone that deals 4d6+4 fire damage (DC 40 Reflex check save), its second action to fly in a U-shape in a random direction, and its third action to release another gout of flame."

```

```encounter-table
name: Floating Flamethrower
creatures:
  - 1: Floating Flamethrower
```

