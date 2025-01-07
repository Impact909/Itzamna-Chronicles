---
title: "Harbor Seal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a4BDrxRP0EkKyf7C" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Harbor Seal"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Harbor Seal"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision, Scent (Imprecise) 20 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +10, Stealth: +8"
abilityMods: [4, 3, 3, -4, 1, 3]
speed: 15 feet,  swim 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +9, __Ref__ +11, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  A harbor seal can hold its breath for 30 minutes."

  - name: "Whisker Sense"
    desc: "  A harbor seal can use its whiskers to sense vibrations as a precise sense at the listed range, but only underwater."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d8 + 4 piercing plus grab"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  40 feet.\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Aquatic Feast"
    desc: "`pf2:1`  **Requirements** The harbor seal has a Medium or smaller creature [[Conditions/Grabbed|Grabbed]] in its jaws\n* * *\n\n**Effect** The harbor seal Swims up to 10 feet, carrying its grabbed creature along with it dealing 1d8 slashing damage (DC 18 Fortitude check save)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Harbor Seal
creatures:
  - 1: Harbor Seal
```




