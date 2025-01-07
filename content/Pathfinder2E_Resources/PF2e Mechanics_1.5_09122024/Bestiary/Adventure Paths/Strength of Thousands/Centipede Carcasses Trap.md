---
title: Centipede Carcasses Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #169: Kindled Magic
aliases: "Actor.DeESe1AfdK89Xxxm" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Centipede Carcasses Trap"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +9, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three giant centipede carcasses have wire springs that pull out and fling their sharpened legs around the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Nature check (trained) to bend the centipede carapace so the wire can't pull out any more legs, or DC 21 Thievery check (expert) to cut the springy wires. After all three carcasses are disabled (regardless of the check used), the trap is deactivated. The trap automatically deactivates after 10 rounds."
attacks:
  - name: ""

  - name: "Volley of Legs"
    desc: "`pf2:r` **Trigger** A carcass is touched or jostled\n* * *\n\n**Effect** Each creature within 30 feet of any centipede carcass takes 4d4 piercing damage (DC 22 Reflex check save), and the area becomes difficult terrain due to the many sharpened legs on the ground. Each creature that Strides more than 10 feet through the area must succeed at a DC 20 Acrobatics check check or take 1d4 piercing damage.\n\nThe trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) Each creature within 30 feet of a centipede carcass that hasn't been disabled takes 6d4 piercing damage (DC 22 Reflex check save)."

```

```encounter-table
name: Centipede Carcasses Trap
creatures:
  - 1: Centipede Carcasses Trap
```

