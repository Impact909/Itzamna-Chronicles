---
title: "Giant Leech"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LjuMQojinFnzWRIl" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Giant Leech"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Leech"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8, Stealth: +7"
abilityMods: [4, 1, 3, -5, 1, -5]
speed: 5 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +9, __Ref__ +7, __Will__ +5"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32; __Weaknesses__ salt 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mouth"
    desc: "+10 ()\n__Damage__  1d4 + 6 piercing plus grab"

  - name: "Blood Drain"
    desc: "`pf2:1`  **Requirements** The giant leech has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The giant leech drains blood from the creature it has grabbed. This deals 2d4 damage. A creature that has its blood drained by a giant leech is [[Conditions/Drained|Drained 1]] until it receives any kind or amount of healing."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Leech
creatures:
  - 1: Giant Leech
```



Capable of growing to lengths of nearly 5 feet, giant leeches have circular maws filled with hook-like teeth. They prefer to dwell in stagnant or slow-moving shallow water or in damp, moist undergrowth. Horses and larger animals are their favorite prey, but they won't balk at a chance to latch onto a human- or halfling-sized meal.
