---
title: Collapsing Structure
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #167: Ready? Fight!
aliases: "Actor.FUjJ3Fi4WTYzndv8" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Collapsing Structure"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 20
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "+20 (master) to notice cracks forming in the walls of the structure as Mogaru approaches"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Mogaru brushes against a structure, severely compromising the building's stability and possibly causing it to collapse."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Athletics check (master), DC 43 Crafting check (master), or Engineering Lore (master) to brace the structure to reduce the risk of collapse until the end of the creature's next turn. The DC of the flat check for this round (see Routine) is increased by 4 on a success, or by 8 on a critical success. Increasing the flat check DC to 21 or higher stabilizes the structure, ending this hazard."
attacks:
  - name: ""

  - name: "Shake Apart"
    desc: "`pf2:r` **Trigger** Mogaru applies any amount of force to the structure\n* * *\n\n**Effect** The building trembles. The floors of the building and the streets within 30 feet of the building become difficult terrain; creatures on this difficult terrain take a -2 circumstance penalty to attack rolls, AC, and skill checks. The hazard rolls initiative."

  - name: "Routine"
    desc: "(1 action) The GM rolls a DC 9 Flat check to determine if the building collapses, increasing the DC as listed above. On a successful check, dust and debris fall within the building and 30 feet around it, providing concealment and dealing 6d6 bludgeoning damage to 12d6 bludgeoning damage to 2d4 randomly chosen targets instead (DC 35 Reflex check save; on a critically failed Reflex save, the creature is restrained by rubble until freed [Force Open DC 38, Escape DC 35])."
  - name: "Reset"
    desc: "The building becomes susceptible to Shake Apart again 1d6 rounds after it is stabilized."
```

```encounter-table
name: Collapsing Structure
creatures:
  - 1: Collapsing Structure
```

