---
title: Dance Of Death
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.XarNjionzsMyrfI5" 
level: 16
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Dance Of Death"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 32
sourcebook: "_Pathfinder GM Core_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An eerie orchestra compels all who hear it to dance until they collapse from exhaustion."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Intimidation check (expert) three times to frighten dancers and spectral musicians alike away from participating in the deadly performance, DC 40 Performance check (master) twice to produce a tune discordant enough to disrupt the compulsion, or DC 42 Religion check (master) three times to banish the spirits with prayers"
attacks:
  - name: ""

  - name: "Prelude"
    desc: "`pf2:r` (auditory, incapacitation, occult) **Trigger** A creature approaches within 30 feet of the orchestra\n* * *\n\n**Effect** The orchestra compels all creatures that can hear it to begin dancing. Each creature must attempt a DC 41 Will check save, with the following effects. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Off-Guard|Off-Guard]] and cannot use reactions. Additionally, it must spend 1 of its actions each round dancing. Dancing is a move action that allows the creature to Stride up to half its Speed.\n\n**Failure** As success, except the creature must spend 2 of its actions each round dancing.\n\n**Critical Failure** As failure, except the creature must spend 3 of its actions each round dancing."

  - name: "Routine"
    desc: "(1 action; auditory, incapacitation, mental, occult) The orchestra performs a raucous tune, compelling all creatures that can hear it to spend actions dancing. Each round, creature must attempt a DC 37 Will check save; the results of this save modify the number of actions that the creature must spend dancing each round. If this would cause the creature to spend more actions dancing than it can use on its turn, the creature takes 10d6 damage (or double that on a critical failure) from moving faster than its body can manage.\n* * *\n\n**Critical Success** The creature decreases the number of actions it must spend dancing by 1.\n\n**Success** No effect.\n\n**Failure** The creature increases the actions it must spend dancing by 1.\n\n**Critical Failure** The creature increases the actions it must spend dancing by 2."
  - name: "Reset"
    desc: "The eerie orchestra spends an hour retuning its phantasmal instruments, after which it is ready to begin its routine again."
```

```encounter-table
name: Dance Of Death
creatures:
  - 1: Dance Of Death
```

