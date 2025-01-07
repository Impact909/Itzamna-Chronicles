---
title: "Sewer Ooze (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.C6crmU4IRvVazIVp" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Sewer Ooze (BB)"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Sewer Ooze (BB)"
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
sourcebook: "_Pathfinder Beginner Box_"
ac: 8
armorclass:
  - name: AC
    desc: "8; __Fort__ +9, __Ref__ +1, __Will__ +3"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  acid,  critical hits,  unconscious,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A sewer ooze can sense nearby motion through vibration and air movement, allowing it to fight as well as if it could see. However, a sewer ooze can't see, so effects that depend on vision or seeing don't work on it."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+9 ()\n__Damage__  1d6 + 1 bludgeoning 1d4 acid"

  - name: "Filth Wave"
    desc: "`pf2:1`  The sewer ooze unleashes a wave of filth, covering all creatures within 20 feet of itself. Each creature in the area must succeed at a DC 17 Reflex check save or take 1d4 acid damage and a -10-foot penalty to its Speeds for 1 minute (on a critical failure, the creature also falls over and gains the [[Conditions/Prone|Prone]] condition). A creature can Interact to clean someone off. This decreases the Speed penalty to -5 feet after 1 action, or to no penalty after 2 actions. After using Filth Wave, the ooze can't use it again for 1 minute.\n\n[[Bestiary Effects/Effect_ Filth Wave|Effect: Filth Wave]]"
 
```

```encounter-table
name: Sewer Ooze (BB)
creatures:
  - 1: Sewer Ooze (BB)
```



These amorphous masses of sewage and detritus make their way through filthy culverts beneath cities. Some grow to enormous sizes and have insatiable appetites.
