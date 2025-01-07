---
title: Dart Barrage
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.7sQ3BCTK8WhsGakL" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Dart Barrage"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +13, __Ref__ +7, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60, (BT 30) to destroy the seal and disable the trap; __Hardness__ 10; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: "(trained) or DC 23 Perception check (trained) to notice scratches around the musical pipes and a slight give to the seal"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four dart-loaded pipes hidden in the diagonal walls are connected to a pressure plate under the brass seal in the room's center."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Thievery check (trained) to disable the pressure plate, or four DC 18 Thievery check (trained) checks to plug the dart launchers"
attacks:
  - name: ""

  - name: "Dart Volley"
    desc: "`pf2:r` **Trigger** More than two Small or larger creatures step on the brass seal.\n* * *\n\n**Effect** The trap makes up to four dart Strikes against creatures standing on the seal, then rolls initiative."
  - name: "Melee"
    desc: "Dart +12 () "

  - name: "No MAP"
    desc: "passive Darts are unaffected by Multiple Attack Penalty"

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action for each disabled launcher. On each of the trap's actions, it fires one dart at a creature in the center of the room."
  - name: "Reset"
    desc: "The trap runs out of darts after 4 rounds of firing and must be reset manually by dismantling the walls to reload the launchers. If at any point there are no longer more than two creatures placing weight on the floor, the trap ceases firing but remains armed, ready to resume firing its remaining darts once triggered again."
```

```encounter-table
name: Dart Barrage
creatures:
  - 1: Dart Barrage
```

