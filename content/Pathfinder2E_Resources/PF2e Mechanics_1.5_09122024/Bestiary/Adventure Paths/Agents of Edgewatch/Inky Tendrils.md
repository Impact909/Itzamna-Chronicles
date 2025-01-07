---
title: Inky Tendrils
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #162: Ruins of the Radiant Siege
aliases: "Actor.Am5pAeviWdYfFNyI" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Inky Tendrils"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[magical]]
modifier: 32
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +36, __Ref__ +39, "
hp: 80
health:
  - name: ""
  - name: "HP"
    desc: "80; __Hardness__ 5; __Immunities__  object immunities,  poison"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: " +32"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Six giant tentacles reach up from the ink lake, grabbing any foes in reach and dragging them underwater."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Athletics check (legendary) or Acrobatics (master) to tie one tentacle into a knot, rendering it useless, or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 44) to counteract one tentacle.\n\nThe death of the Daemonic Rumormonger permanently dispels all the inky tendrils."
attacks:
  - name: ""
  - name: "Melee"
    desc: "Tentacle +37 (reach 15 feet) "

  - name: "Black Ink Delirium"
    desc: "passive (poison) **Saving Throw** DC 38 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 6d6 poison damage and [[Conditions/Confused|Confused]] (1 round)"

  - name: "Inky Imitator"
    desc: "action (arcane) The inky tendrils cast a 10th-rank [[Spells/Duplicate Foe|Duplicate Foe]] spell (DC 40 Fortitude check) on the target; on a failed save, a simulacrum of the target made from dripping ink and clockwork scraps emerges from any other spot (tendrils' choice) in the lake.\n\nThe tendrils don't need to Sustain the Spell; the duplicate exists for 1 minute or until it is destroyed before collapsing into a puddle of ink and scrap metal."

  - name: "Grab"
    desc: "action **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "Constrict"
    desc: "action 2d8+10 bludgeoning plus black ink delirium, DC 42 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Tendrils Come Alive"
    desc: "`pf2:r` **Trigger** A non-daemonic creature moves within 15 feet of the shoreline\n* * *\n\n**Effect** The hazard makes a tentacle Strike against the triggering creature and the hazard rolls initiative."

  - name: "Routine"
    desc: "(6 actions) The hazard loses 1 action for every tentacle that is disabled or destroyed. The tentacles can combine their actions to use the hazard's Inky Imitator ability. A broken tentacle can still Strike, but it can't Grab. This hazard takes no multiple attack penalty."

```

```encounter-table
name: Inky Tendrils
creatures:
  - 1: Inky Tendrils
```

