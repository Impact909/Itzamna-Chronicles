---
title: "Sicklehand Construct"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.b9YJM5HeqbXgh8un" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Sicklehand Construct"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Sicklehand Construct"
level: "Creature 0"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +5"
abilityMods: [1, 3, 1, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +9, __Will__ +4"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ fire 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x Wooden Sickle"
abilities_mid:
  - name: ""
  - name: "Critical Vulnerability"
    desc: "  A critical hit damages the construct's controls, making it [[Conditions/Clumsy|Clumsy 1]] until repaired. Additional critical hits increase this value, up to [[Conditions/Clumsy|Clumsy 4]]."

  - name: "Ridden Construct"
    desc: "  The construct is piloted by a [[Monster Core/Leaf Leshy|Leaf Leshy]] who can be targeted separately but has greater cover. The leshy can't take actions of their own while inside the construct, other than to leave it, which takes 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wooden Sickle"
    desc: "+8 (agile, finesse, trip)\n__Damage__  1d4 + 1 slashing"

  - name: "Menacing Sickles"
    desc: "  The construct deals an additional 1d4 precision damage to [[Conditions/Off-Guard|Off-Guard]] or [[Conditions/Prone|Prone]] creatures."
 
```

```encounter-table
name: Sicklehand Construct
creatures:
  - 1: Sicklehand Construct
```




