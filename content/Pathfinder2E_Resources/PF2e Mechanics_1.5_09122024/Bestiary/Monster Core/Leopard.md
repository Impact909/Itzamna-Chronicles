---
title: "Leopard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gIKrehQrrkmOzlk6" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Leopard"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Leopard"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +7, Stealth: +8"
abilityMods: [3, 4, 2, -4, 1, -2]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +10, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (finesse)\n__Damage__  1d10 + 3 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile, finesse)\n__Damage__  1d6 + 3 slashing"

  - name: "Maul"
    desc: "`pf2:1`  The leopard makes two claw Strikes against a creature it has [[Conditions/Grabbed|Grabbed]]. Both count toward its multiple attack penalty, but the penalty increases only after both attacks are made."

  - name: "Pounce"
    desc: "`pf2:1`  The leopard Strides and makes a Strike at the end of that movement. If the leopard began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "Sneak Attack"
    desc: "  The leopard deals 1d4 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Leopard
creatures:
  - 1: Leopard
```



Leopards are among the smallest of the big cats, yet they are still dangerous creatures to tangle with. Leopard statistics can also be used for black panthers, white-spotted snow leopards, or tawny-coated cougars.

* * *

Few predators of the natural world can match the cat's talent for stalking and stealth. Large cats can be found in almost any environment, usually keeping their distance from settlements. When civilization encroaches onto a big cat's hunting grounds, the animals are often driven to making desperate attacks against unwary travelers.
