---
title: Convergence Lattice
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #156: The Apocalypse Prophet
aliases: "Actor.aLrTAUlf8pLjsT0q" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Convergence Lattice"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 34
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +33, __Ref__ +28, __Will__ +36"
hp: 460
health:
  - name: ""
  - name: "HP"
    desc: "460; __Hardness__ 30; __Immunities__  object immunities (except mental); __Weaknesses__ mental 30"
perception:
  - name: ""
  - name: "Stealth DC 34" 
    desc: "(master) to realize the lattice is a complex clockwork before it begins to move; noticing the lattice itself is DC 0."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A complex clockwork of bright metal and delicately carved gemstones, the lattice's interlocking gears begin to whir as golden runes glow across its surface."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Thievery check (master) or DC 35 Religion check (master) four times to obliterate each of the four key runes.\n\nA DC 45 Thievery check (legendary) check (or breaking the lattice) stops the clockwork's movement and prevents it from resetting, but doesn't stop its current activation."
attacks:
  - name: ""

  - name: "Begin Convergence"
    desc: "`pf2:r` **Trigger** A creature that is not [[Conditions/Controlled|Controlled]] by the convergence lattice sees it\n* * *\n\n**Effect** The lattice's clockworks begin to move and it rolls for initiative."

  - name: "Routine"
    desc: "(3 actions) The _convergence lattice_ uses its first action to call for aid. Each convergent creature within 100 feet of the lattice Strides toward the lattice as a reaction. Creatures thus called continue to move toward the lattice on their turn each round until they are adjacent to it, at which point they defend it with their lives.\n\nThe lattice uses its second action to deal 16d6 mental damage (DC 42 Will check save) to a non-convergent creature within 100 feet. This damage is nonlethal; a creature knocked out by this damage doesn't gain the dying condition and is automatically [[Conditions/Controlled|Controlled]] by the convergence lattice when they awaken.\n\nThe lattice uses its third action to make the same attack against a second non-convergent creature within 100 feet; if there isn't such a second creature, it doesn't take its third action."
  - name: "Reset"
    desc: "The _convergence lattice_ deactivates and resets after there are no uncontrolled targets within line of sight for 1 minute."
```

```encounter-table
name: Convergence Lattice
creatures:
  - 1: Convergence Lattice
```

