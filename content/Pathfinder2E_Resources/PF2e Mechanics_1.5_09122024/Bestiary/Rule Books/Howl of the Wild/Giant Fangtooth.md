---
title: "Giant Fangtooth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.K6b40YpXuJLrr0PO" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Giant Fangtooth"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Giant Fangtooth"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +14"
abilityMods: [5, 2, 3, -5, 2, -1]
speed:  swim 35 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +11, __Will__ +8"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""

  - name: "Sunless Sight"
    desc: "  In an area of bright light, the giant fangtooth is [[Conditions/Blinded|Blinded]] and [[Conditions/Slowed|Slowed 1]]."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+15 ()\n__Damage__  2d8 + 5 piercing plus deep-puncture,grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8 piercing, DC 21 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Deep Puncture"
    desc: "  Creatures critically hit by the fangtooth's bite take an additional 1d8 persistent bleed damage."
 
```

```encounter-table
name: Giant Fangtooth
creatures:
  - 1: Giant Fangtooth
```



A single bite from this creature's signature fangs can cause death by blood loss within minutes; what's worse, the giant fangtooth is willing to attack creatures far larger than itself.
