---
title: "Giant Ant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.d5wHj2R9P0oCtUap" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Giant Ant"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Ant"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8, Survival: +7"
abilityMods: [4, 1, 4, -5, 1, -4]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +7, __Will__ +5"
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

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+9 ()\n__Damage__  1d8 + 4 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+9 (agile)\n__Damage__  1d6 + 4 piercing plus giant-ant-venom"

  - name: "Giant Ant Venom"
    desc: " (poison) **Saving Throw** DC 18 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d8 poison and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d10 poison and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 1d12 poison and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "Haul Away"
    desc: "`pf2:1`  **Requirements** The giant ant has a Large or smaller creature grabbed\n* * *\n\n**Effect** The giant ant Strides up to its full Speed, carrying the grabbed creature with it. It is [[Conditions/Encumbered|Encumbered]] if the grabbed creature is Medium or larger."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Ant
creatures:
  - 1: Giant Ant
```



Giant ants are much like their smaller kin in their industrious habits, though growing to the size of ponies makes them much deadlier.

* * *

Ants are industrious insects that aid the natural processes of decay and renewal.
