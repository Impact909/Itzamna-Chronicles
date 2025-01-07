---
title: "Mechanical Carny"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y9g4X87ANy4TB3ak" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Mechanical Carny"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Mechanical Carny"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision"
languages: "Common; (can speak pre-recorded phrases only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +9, Performance: +6"
abilityMods: [3, 1, 0, -5, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +11, __Will__ +4"
hp: 33
health:
  - name: ""
  - name: HP
    desc: "33; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 6; __Resistances__ physical 3 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Haywire"
    desc: "  A severely damaged mechanical carny has a chance of malfunctioning. If a mechanical carny has 15 or fewer Hit Points at the start of its turn, it must succeed at a DC 5 Flat check check or go haywire. A haywire mechanical carny wildly attacks the nearest living creature, or the nearest object if no creatures are nearby. It takes a -1 circumstance penalty to Strikes but deals an additional 1d6 bludgeoning damage plus [[Bestiary Ability Glossary/Knockdown|Knockdown]]. This effect lasts 10 minutes or until the mechanical carny is destroyed.\n\n[[Bestiary Effects/Effect_ Haywire|Effect: Haywire]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spring-loaded Fist"
    desc: "+11 (nonlethal, reach 10 feet)\n__Damage__  2d4 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Headbutt"
    desc: "+11 ()\n__Damage__  2d4 + 4 bludgeoning"
 
```

```encounter-table
name: Mechanical Carny
creatures:
  - 1: Mechanical Carny
```



Mechanical carnies are constructs manufactured to serve as entertainers, cleaners, and guards at carnivals and circuses. The first of these constructs was created by a gnome inventor who yearned for a tireless companion who could make her laugh and smile. Her invention was so successful that it has spawned countless imitations and knockoffs throughout the Inner Sea, and mechanical carnies of some form or another are a staple throughout metropolitan lands in both Avistan and Garund.
