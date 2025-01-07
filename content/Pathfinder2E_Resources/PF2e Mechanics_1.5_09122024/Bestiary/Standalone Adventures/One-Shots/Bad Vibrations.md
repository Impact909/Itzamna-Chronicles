---
title: Bad Vibrations
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: A Fistful of Flowers
aliases: "Actor.51VfWRYCJkNgcYpx" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: A Fistful of Flowers"
name: "Bad Vibrations"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder Adventure: A Fistful of Flowers_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +6, "
hp: 16
health:
  - name: ""
  - name: "HP"
    desc: "16, HP per crystal; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ sonic 5"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The three larger crystals on the table begin to vibrate and emit a swiftly growing peal of sound."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 17 Thievery check (trained) or DC 17 Occultism check (trained) to disrupt the magic enchanting one of the crystals, or DC 20 Performance check (trained) by a character who can cast [[Spells/Counter Performance|Counter Performance]] to use sound to redirect the noise back into the crystal, or [[Spells/Dispel Magic|Dispel Magic]] (2nd level, DC 18) to counteract a crystal."
attacks:
  - name: ""

  - name: "Shrill Chime"
    desc: "`pf2:r` **Trigger** A creature other than Darius or one of his homonculi approaches within 5 feet of the table or attempts to Interact with the crystals in any way other than to attempt to disable the hazard.\n* * *\n\n**Effect** The three large crystals on the table begin vibrating and humming. The hazard rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The hazard loses 1 action for each crystal that's disabled or destroyed. On each of the trap's actions, one of the crystals fires a blast of sound at a single Small or larger creature in the room. The target is randomly determined and takes 1d8 sonic damage (DC 20 Fortitude check); a target who critically fails this save is [[Conditions/Deafened|Deafened]] for 1 minute. At the end of the hazard's routine, attempt a DC 10 Flat check. On a success, one of the crystals shatters and is destroyed."

```

```encounter-table
name: Bad Vibrations
creatures:
  - 1: Bad Vibrations
```

