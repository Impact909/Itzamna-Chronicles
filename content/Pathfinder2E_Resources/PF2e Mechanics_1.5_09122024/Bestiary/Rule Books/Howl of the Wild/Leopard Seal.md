---
title: "Leopard Seal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.m8tlUIj6m578puts" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Leopard Seal"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Leopard Seal"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 40 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +14, Stealth: +10"
abilityMods: [6, 4, 3, -4, 1, 2]
speed: 15 feet,  swim 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +12, __Ref__ +14, __Will__ +8"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  A leopard seal can hold its breath for 30 minutes."

  - name: "Protective Blubber"
    desc: "  A leopard seal treats environmental cold effects as if they were one step less extreme (incredible cold becomes extreme, extreme cold becomes severe, and so on)."

  - name: "Whisker Sense"
    desc: "  A leopard seal can use its whiskers to sense vibrations as a precise sense at the listed range, but only underwater."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  2d8 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+12 (agile)\n__Damage__  2d6 + 6 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  50 feet.\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Predatory Slam"
    desc: "`pf2:2`  **Requirements** The leopard seal is in water\n* * *\n\n**Effect** The leopard seal travels up to 40 feet, ending its movement on land. Enemies adjacent to the leopard seal when it ends its movement take 2d10 bludgeoning damage (DC 21 Reflex check save) and are knocked [[Conditions/Prone|Prone]] on a failure."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Leopard Seal
creatures:
  - 1: Leopard Seal
```




