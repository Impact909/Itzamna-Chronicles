---
title: The Winder
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder #161: Belly of the Black Whale
aliases: "Actor.sAvmKTDjI3yq99Ya" 
level: 19
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "The Winder"
level: "Hazard 19"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[mechanical]]
modifier: 31
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +32, __Ref__ +35, "
hp: 250
health:
  - name: ""
  - name: "HP"
    desc: "250; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 31" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A large metallic arm, 20 feet long, is set into the floor. It rotates around the room to wind up nearby clockwork creatures."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 50 Thievery check (master) to deactivate the system, or DC 40 Athletics check (legendary) to jam the gears for 1 round"
attacks:
  - name: ""

  - name: "Wind Up"
    desc: "`pf2:r` **Trigger** A creature other than the Rumormonger enters the room, or the Rumormonger commands the device to activate\n* * *\n\n**Effect** The Winder rolls initiative."

  - name: "Wind"
    desc: "action The Winder winds a clockwork creature in the room. If the creature is currently inactive, this activates the creature, allowing it to act normally for 1d4 rounds. If already active, this instead increases the number of rounds the clockwork creature remains active by 1d4."

  - name: "Routine"
    desc: "(1, 2, or 4 actions, depending on the encounter's threat level) The Winder uses each of its actions to Wind clockwork assassins in the room, starting with inactive ones."
  - name: "Reset"
    desc: "The Winder resets as soon as no creatures remain in the room."
```

```encounter-table
name: The Winder
creatures:
  - 1: The Winder
```

