---
title: Spectral Archers
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #177: Burning Tundra
aliases: "Actor.7mrYrd0rSkrglTJ8" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Spectral Archers"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 28
sourcebook: "_Pathfinder #177: Burning Tundra_"
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
  - name: "Stealth DC 28" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Ghostly soldiers wielding crossbows manifest within the towers that flank the gatehouse and rain bolts down upon intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 31 Intimidation check (expert) to cow the archers into fleeing or DC 28 Religion check (expert) to temporarily banish the spirits"
attacks:
  - name: ""

  - name: "Rain of Bolts"
    desc: "`pf2:r` **Trigger** A creature attacks the graveknights in area **G1** or enters the castle\n* * *\n\n**Effect** The haunt makes a spectral bolt Strike against the triggering creature, then rolls initiative."

  - name: "Routine"
    desc: "action (1 action) The hazard fires one bolt at every creature in a 30-foot-by-30-foot area in front of the gate as 1 action. Because the spectral archers fire bolts continuously, the haunt can also use the Continuous Barrage free action (below) to fire bolts at each creature during that creature's turn."

  - name: "Continuous Barrage"
    desc: "`pf2:0` **Trigger** A creature in front of the gate finishes an action\n* * *\n\n**Effect** The haunt makes a spectral bolt Strike against the triggering creature."
  - name: "Melee"
    desc: "Spectral Bolt +20 () No multiple attack penalty."


  - name: "Reset"
    desc: "The haunt vanishes permanently if the graveknights are destroyed. Otherwise, it returns after 1 hour."
```

```encounter-table
name: Spectral Archers
creatures:
  - 1: Spectral Archers
```

