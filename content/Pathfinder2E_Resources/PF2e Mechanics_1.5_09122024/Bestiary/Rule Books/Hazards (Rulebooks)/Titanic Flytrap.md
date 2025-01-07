---
title: Titanic Flytrap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.Sep8tDGAsergf4PK" 
level: 4
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Titanic Flytrap"
level: "Hazard 4"


trait_01: [[environmental]]
modifier: 15
sourcebook: "_Pathfinder GM Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +8, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56; __Immunities__  mental; __Resistances__ acid 20, fire 10"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "On the surface, a titanic flytrap appears to be a patch of the more common flytrap plant, but beneath murky waters it hides a far larger set of jaws, reaching 10 feet across, reinforced with woody branches and lined with paralytic hairs."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Survival check (trained) to mislead the flytrap's sense of weight and pressure"
attacks:
  - name: ""

  - name: "Snap Shut"
    desc: "`pf2:r` **Trigger** A Small or Medium creature moves into a square that is within reach of the flytrap's hidden jaws\n* * *\n\n**Effect** The flytrap's jaws snap shut, making a jaws Strike against the triggering creature."
  - name: "Melee"
    desc: "Jaws +17 () "

  - name: "Devour"
    desc: "passive The target is trapped by the flytrap's jaws, gaining the [[Conditions/Grabbed|Grabbed]] condition until it Escapes (DC 21). Additionally, it is exposed to the titanic flytrap toxin from the hundreds of tiny hairs that line the inside of its leaves. If the flytrap's jaws Strike was a critical success, the target takes a –2 circumstance penalty to its saving throws against this poison. At the end of each of the target's turns that it remains grabbed, the target takes 3d6 acid damage."

  - name: "Titanic Flytrap Toxin"
    desc: "passive (contact, poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Stunned|Stunned 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Stunned|Stunned 2]] (1 round)\n\n**Stage 3** 4d6 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"


  - name: "Reset"
    desc: "1 hour (or longer, after a large meal)"
```

```encounter-table
name: Titanic Flytrap
creatures:
  - 1: Titanic Flytrap
```

