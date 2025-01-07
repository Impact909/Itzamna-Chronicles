---
title: Flying Guillotine
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.Uf1C44RWT0tNHjup" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Flying Guillotine"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +9, __Ref__ +17, "
hp: 52
health:
  - name: ""
  - name: "HP"
    desc: "52; __Hardness__ 13; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained) or DC 23 Perception check (expert) to spot the glyph"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An invisible magical glyph on the guillotine's blade detects living creatures in the room, which causes the guillotine to fly off its hinges and attack."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Thievery check (trained) to erase the glyph (which requires a successful unarmed attack roll if the blade is already active) or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 20) to counteract it. The trap has a secret bypass known only to Ralso and Pratchett: as long as the guillotine can see a creature in the room touching thumb and pinky together with an empty hand, it remains dormant."
attacks:
  - name: ""

  - name: "Flying Blade"
    desc: "`pf2:r` (arcane, attack) **Trigger** A living creature enters the room\n* * *\n\n**Effect** One round after a creature enters the room, the door to the room slams shut and locks (two Thievery checks to pick), and the guillotine blade detaches from its housing and begins flying around the room as the trap rolls initiative."

  - name: "Speed"
    desc: "passive fly 20 feet"
  - name: "Melee"
    desc: "Guillotine Blade +15 () "

  - name: "Routine"
    desc: "(1 action) The blade [[Actions/Fly|Flies]] up to 20 feet and Strikes any creatures whose squares it passes through. It cannot target the same creature more than once per round. The blade cannot be grappled and doesn't take a multiple attack penalty."
  - name: "Reset"
    desc: "After 1 minute, the trap deactivates, though the door remains locked. The trap rearms itself each day at dawn."
```

```encounter-table
name: Flying Guillotine
creatures:
  - 1: Flying Guillotine
```

