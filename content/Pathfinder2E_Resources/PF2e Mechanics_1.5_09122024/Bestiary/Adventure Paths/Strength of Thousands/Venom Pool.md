---
title: Venom Pool
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #174: Shadows of the Ancients
aliases: "Actor.YgqR5ESANrpmN7cj" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Venom Pool"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 30
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
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
  - name: "Stealth DC 30" 
    desc: "(legendary) to distinguish between the hazard and the oozes within it; DC 0 Perception check to notice the pool"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A shallow, foul-smelling puddle of toxic acid blocks a narrow hall (marked with a dotted line on the map), and poison bursts from it when disturbed."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Crafting check (master) or DC 42 Survival check (legendary) to neutralize the acid while within reach of it. Three successes using either skill (or a combination of both) destroys the hazard."
attacks:
  - name: ""

  - name: "Deadly Footing"
    desc: "passive The area of the venom pool is difficult terrain, and each creature moving through it takes 10 acid for every square of its area that it moves into."

  - name: "Poison Puff"
    desc: "`pf2:r` **Trigger** A creature moves through any square in the hazard's space\n* * *\n\n**Effect** The pool produces a 9th-rank [[Spells/Toxic Cloud|Toxic Cloud]]; (DC 40 Fortitude check) at its center. It then rolls initiative."

  - name: "Routine"
    desc: "(2 actions) The hazard uses its first action to spread 10 feet down the hallway in both directions. Once out of the hall, each side spreads in a random direction each round, but they don't go through doors. The hazard uses its second action to move the center of the [[Spells/Toxic Cloud|Toxic Cloud]] up to 20 feet in any direction to which any part of the pool has line of effect (normally, to encompass the greatest number of characters). If the _cloudkill_ isn't present, it instead uses its second action to produce a new _cloudkill_, as Poison Puff."
  - name: "Reset"
    desc: "The hazard ends after 1 minute, contracting to its original size and keeping still until disturbed again."
```

```encounter-table
name: Venom Pool
creatures:
  - 1: Venom Pool
```

