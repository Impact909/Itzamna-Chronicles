---
title: Toxic Furnace
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Crown of the Kobold King
aliases: "Actor.cgYJLUhnR852ka0V" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Toxic Furnace"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 5
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +11, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56, Furnace BT 28, Vent Hardness 10, Vent HP 18 (BT 9); __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 5" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The smoking furnace begins to hiss and click, and its vents swivel and adjust to spew toxic fumes in the direction of intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Thievery check (trained) to render one of the vents useless, or DC 25 Athletics check to wrench and bend a vent until it no longer functions"
attacks:
  - name: ""

  - name: "Spew Toxins"
    desc: "`pf2:r` **Trigger** A visible living creature enters the room, or a Stealthy creature fails to remain [[Conditions/Hidden|Hidden]] from the toxic furnace with a DC 25 Stealth check check (the trap's sensors have darkvision and lifesense);\n\n**Effect** One of the toxic furnace's vents swivels to aim at the triggering creature and then spews a gout of boiling toxin at the target. The toxic furnace then rolls initiative."
  - name: "Melee"
    desc: "Boiling Toxin +17 (range 30 feet) "

  - name: "Routine"
    desc: "(3 actions) The trap loses 1 action for each disabled vent. On each of the trap's actions, a vent spews a gout of boiling toxin at a living creature in sight of it. It can't target a single creature more than once per round, so if there aren't enough viable targets for all 3 actions, the trap loses those unspent actions."
  - name: "Reset"
    desc: "The trap resets after 1 minute, during which it sees no creatures to target."
```

```encounter-table
name: Toxic Furnace
creatures:
  - 1: Toxic Furnace
```

