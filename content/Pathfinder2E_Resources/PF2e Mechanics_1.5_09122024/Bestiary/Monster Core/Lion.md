---
title: "Lion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BMEcctLmCT5yKL30" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Lion"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Lion"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +9, Stealth: +10"
abilityMods: [4, 3, 2, -4, 2, -2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +10, __Will__ +7"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d10 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile)\n__Damage__  1d8 + 6 slashing"

  - name: "Pack Attack"
    desc: "  The lion deals 1d4 extra damage to any creature that's within reach of at least two of the lion's allies."

  - name: "Pounce"
    desc: "`pf2:1`  The lion Strides and makes a Strike at the end of that movement. If the lion began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "Sneak Attack"
    desc: "  The lion deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Lion
creatures:
  - 1: Lion
```



Lions are cooperative hunters, ambushing dangerous prey in groups of lionesses that work in tandem to trap and kill their prey. Male lions are typically larger, with long manes, and when they hunt, they tend to do so on their own.

* * *

Few predators of the natural world can match the cat's talent for stalking and stealth. Large cats can be found in almost any environment, usually keeping their distance from settlements. When civilization encroaches onto a big cat's hunting grounds, the animals are often driven to making desperate attacks against unwary travelers.
