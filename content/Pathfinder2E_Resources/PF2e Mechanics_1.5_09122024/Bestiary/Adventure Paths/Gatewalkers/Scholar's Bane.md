---
title: Scholar's Bane
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - illusion
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #187: The Seventh Arch
aliases: "Actor.XiZZyEocOkWhUrr2" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Scholar's Bane"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[illusion]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 14
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +12, __Ref__ +8, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20; __Hardness__ 6; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 14" 
    desc: "(trained) to notice magical sensors hidden within four of the carvings' eyes"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Illusion magic overwhelms the minds of particularly intelligent creatures, forcing them to relive every intellectual failure and shame they've ever suffered."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Thievery check (trained) to carve out one eye sensor, DC 22 Arcana check or DC 22 Occultism check (trained) to blank out one's mind (disables trap for self only), or [[Spells/Dispel Magic|Dispel Magic]] (2nd level; counteract DC 20) to counteract one eye sensor"
attacks:
  - name: ""

  - name: "Reveal Failure"
    desc: "`pf2:r` **Trigger** A creature with an Intelligence score of 10 or greater enters the room\n* * *\n\n**Effect** The trap fills the triggering creature's mind with shameful memories. The creature must succeed at a DC 22 Will check save or take 2d8+2 mental. The trap then rolls initiative."

  - name: "Routine"
    desc: "(4 actions) The trap uses each action to target a creature in the room with an Intelligence score of 10 or greater. A target must succeed at a DC 22 Will check save or take 2d8+2 mental. On a critical failure, the creature takes a –10-foot status penalty to Speed for 1 minute as they stagger under the weight of their failures. The trap loses 1 action for each eye sensor disabled or destroyed."
  - name: "Reset"
    desc: "The trap can function for 10 rounds, which don't need to be consecutive, before it must recharge for 24 hours."
```

```encounter-table
name: Scholar's Bane
creatures:
  - 1: Scholar's Bane
```

