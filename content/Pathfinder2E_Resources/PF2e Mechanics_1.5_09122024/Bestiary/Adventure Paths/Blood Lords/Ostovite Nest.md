---
title: Ostovite Nest
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #181: Zombie Feast
aliases: "Actor.ua9KazINqKixQPP5" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Ostovite Nest"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 11
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 7; __Immunities__  object immunities,  acid,  critical hits,  precision; __Weaknesses__ area damage 5, bludgeoning 5, splash damage 5"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A nest of bones resembling an ant hill contains countless miniscule scavenger vermin with vicious, acid-dripping mandibles."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Athletics check (trained) to topple the mound and destroy it"
attacks:
  - name: ""

  - name: "Skittering Surge"
    desc: "`pf2:r` **Trigger** A creature comes within 15 feet of the nest\n* * *\n\n**Effect** A mass of skittering ostovite hatchlings crawls all over the nest, spewing acid in all directions. Each creature within 30 feet of the nest takes 1d10+4 acid damage (DC 18 Reflex check). A creature who fails the save also takes 1 persistent acid damage. The hazard then rolls initiative."
  - name: "Melee"
    desc: "Acid Spew +11 (range increment 30 feet) "

  - name: "Routine"
    desc: "(1 action) The hazard makes an acid spew Strike against the nearest creature."
  - name: "Reset"
    desc: "The hazard deactivates if there are no targets for its acid spew at the start of its turn. The hatchlings return to the nest, and the hazard resets. If damaged but not destroyed, the nest recovers 1d6 healing Hit Points per hour as the hatchlings repair it."
```

```encounter-table
name: Ostovite Nest
creatures:
  - 1: Ostovite Nest
```

