---
title: "Tiger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JliqyundK241Uk6P" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Tiger"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tiger"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +13, Stealth: +13"
abilityMods: [5, 3, 3, -4, 2, -2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +11, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  1d10 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile)\n__Damage__  1d8 + 7 slashing"

  - name: "Pounce"
    desc: "`pf2:1`  The tiger Strides and makes a Strike at the end of that movement. If the tiger began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "Sneak Attack"
    desc: "  The tiger deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Wrestle"
    desc: "`pf2:1`  The tiger makes a claw Strike against a creature it is [[Conditions/Grabbed|Grabbing]]. If the attack hits, that creature is knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tiger
creatures:
  - 1: Tiger
```



Tigers are solitary and territorial hunters, using their striped hides to blend into the forests and jungles they call home and preferring to attack with surprise.

* * *

Few predators of the natural world can match the cat's talent for stalking and stealth. Large cats can be found in almost any environment, usually keeping their distance from settlements. When civilization encroaches onto a big cat's hunting grounds, the animals are often driven to making desperate attacks against unwary travelers.
