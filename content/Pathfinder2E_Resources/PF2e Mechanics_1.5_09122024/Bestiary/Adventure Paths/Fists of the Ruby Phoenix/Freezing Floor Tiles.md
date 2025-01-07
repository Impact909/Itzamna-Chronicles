---
title: Freezing Floor Tiles
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - cold
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #167: Ready? Fight!
aliases: "Actor.Rb4uLW1FqOAkzRmR" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Freezing Floor Tiles"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[cold]]
trait_02: [[magical]]
trait_03: [[trap]]
modifier: 23
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +33, __Ref__ +30, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40; __Hardness__ 20; __Immunities__  object immunities,  cold; __Weaknesses__ fire 15"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "+23 (expert) or DC 38 Perception check (master) to notice the four sensors"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four remote sensors at each corner of the arena cause bursts of freezing magic to erupt from random tiles on the arena and stop creatures in their tracks."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Thievery check (legendary) or [[Spells/Dispel Magic|Dispel Magic]] (6th level; counteract DC 38) to disable one of the sensors"
attacks:
  - name: ""

  - name: "Frigid Floor"
    desc: "`pf2:r` (cold) **Trigger** Hao Jin signals the beginning of the match.\n* * *\n\n**Effect** The trap rolls initiative."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action per disabled sensor. On each action, the trap causes a random 10-foot-by-10-foot space in the arena to suddenly freeze. Each creature that begins its turn in a frozen space takes 2d6+2 cold damage (DC 40 Reflex check save). A creature that critically fails its save also becomes [[Conditions/Slowed|Slowed 1]] for 1 round; if it was already slowed, the creature instead becomes [[Conditions/Immobilized|Immobilized]] for 1 round. Any amount of fire damage dealt to a slowed or immobilized creature removes the condition. Frozen tiles become unfrozen at the beginning of the trap's next turn."

```

```encounter-table
name: Freezing Floor Tiles
creatures:
  - 1: Freezing Floor Tiles
```

