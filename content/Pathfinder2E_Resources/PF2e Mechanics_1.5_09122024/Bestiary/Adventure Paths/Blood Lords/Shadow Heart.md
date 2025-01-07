---
title: Shadow Heart
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #183: Field of Maidens
aliases: "Actor.oa5vva0i7yxgosK7" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Shadow Heart"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 20
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +21, __Ref__ +15, __Will__ +18"
hp: 72
health:
  - name: ""
  - name: "HP"
    desc: "72; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 10, vitality 10"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A heart of tumorous, shadowy tissue unleashes magic on nearby creatures."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Arcana check or DC 26 Occultism check (expert) to counter the heart's offensive magic, or DC 28 Religion check (trained) to purify the area containing the heart. Four successes are required to disable it; after two successes, the shadow heart can't use its shadow lash Strike."
attacks:
  - name: ""

  - name: "Shadow Pulse"
    desc: "`pf2:r` **Trigger** A creature approaches within 10 feet of the heart\n* * *\n\n**Effect** The heart gives a slow beat, and all creatures in the room must succeed at a DC 30 Will check save or be [[Conditions/Stunned|Stunned 1]] and unable to take reactions for 1 round ([[Conditions/Stunned|Stunned 3]] on a critical failure). The dark heart then rolls initiative."

  - name: "Battering Vortex"
    desc: "action A swirling vortex of shadows forms around the heart, lifting all creatures in the room and slamming them forcefully to the ground, dealing 4d10 bludgeoning damage. Each creature must attempt a DC 30 Fortitude check save. Anyone adjacent to a wall may [[Actions/Grab an Edge|Grab an Edge]] with a successful DC 28 Reflex check save; on a success at Grabbing an Edge, the creature uses a result one step better than the roll of their Fortitude save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is knocked [[Conditions/Prone|Prone]].\n\n**Failure** The creature takes full damage, is knocked prone, and is [[Conditions/Clumsy|Clumsy 1]] for 1 round.\n\n**Critical Failure** The creature takes full damage, is knocked prone, and is [[Conditions/Clumsy|Clumsy 3]] for 1 round."
  - name: "Melee"
    desc: "Shadow Lash +21 (cold, reach 30 feet) "

  - name: "Routine"
    desc: "The shadow heart uses Battering Vortex, and then uses shadow lash on a random creature within range."
  - name: "Reset"
    desc: "The heart deactivates if there are no creatures present in the room. It resets in 1 hour."
```

```encounter-table
name: Shadow Heart
creatures:
  - 1: Shadow Heart
```

