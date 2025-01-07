---
title: "Sewer Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mvp8ucRvxGhRgVvg" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Sewer Ooze"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sewer Ooze"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +1"
abilityMods: [2, -5, 4, -5, 0, -5]
speed: 10 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 8
armorclass:
  - name: AC
    desc: "8; __Fort__ +9, __Ref__ +1, __Will__ +3"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  bleed,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A sewer ooze can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+9 ()\n__Damage__  1d6 + 1 bludgeoning 1d4 acid"

  - name: "Filth Wave"
    desc: "`pf2:1`  **Frequency** once per minute\n* * *\n\n**Effect** The sewer ooze unleashes a wave of filth, covering all creatures in a 20-foot emanation. Each creature in the area must succeed at a DC 17 Reflex check save or take 1d4 acid damage and take a –10-foot penalty to its Speeds for 1 minute (on a critical failure, the creature also falls [[Conditions/Prone|Prone]]).\n\nA creature can spend an Interact action to clean someone off, decreasing the Speed penalty by 5 feet with each action.\n\n[[Bestiary Effects/Effect_ Filth Wave|Effect: Filth Wave]]"
 
```

```encounter-table
name: Sewer Ooze
creatures:
  - 1: Sewer Ooze
```



These amorphous masses of sewage and other detritus make their way through filthy culverts beneath cities large and small.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
