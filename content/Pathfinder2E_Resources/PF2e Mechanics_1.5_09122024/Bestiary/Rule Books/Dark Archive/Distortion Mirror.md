---
title: Distortion Mirror
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Dark Archive
aliases: "Actor.8dft4PMrZPsD0kC0" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Distortion Mirror"
level: "Hazard 14"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 28
sourcebook: "_Pathfinder Dark Archive_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +28, __Ref__ +22, "
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90; __Hardness__ 24; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 38" 
    desc: "0 to notice the mirror"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Fun-house mirrors distort a viewer's reflection, painfully reshaping their body to match what appears in the reflected images."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 38 Thievery check (master) to deface the mirror's pane, or [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 36) to dispel the mirror or counteract the transformation"
attacks:
  - name: ""

  - name: "Painful Transformation"
    desc: "`pf2:r` (attack) **Trigger** A creature is reflected in the mirror\n* * *\n\n**Effect** The triggering creature's body is painfully squished, stretched, and distorted to match their reflection. The creature takes 6d10 + 30 force damage and must attempt a DC 39 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target takes half damage and is [[Conditions/Clumsy|Clumsy 1]] and [[Conditions/Enfeebled|Enfeebled 1]] for 1 round.\n\n**Failure** The target takes full damage and is [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Enfeebled|Enfeebled 2]] for 4 rounds.\n\n**Critical Failure** The target takes double damage and is clumsy 2 and enfeebled 2 for 1 minute. As long as the creature is clumsy or enfeebled, it additionally takes a -10-foot status penalty to its Speeds.\n\nWhen the effects of this trap end, the triggering creature's transformation ends, and its body reverts to its natural form."


  - name: "Reset"
    desc: "1 day"
```

```encounter-table
name: Distortion Mirror
creatures:
  - 1: Distortion Mirror
```

