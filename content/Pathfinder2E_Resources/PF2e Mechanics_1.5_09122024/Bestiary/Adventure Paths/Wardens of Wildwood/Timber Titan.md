---
title: "Timber Titan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lk104IWK279SVZZN" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Timber Titan"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Timber Titan"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[mindless]]
trait_03: [[wood]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17"
abilityMods: [6, -1, 6, -5, 0, -5]
speed: 30 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 26
armorclass:
  - name: AC
    desc: "26 (22 when broken); construct armor; __Fort__ +17, __Ref__ +10, __Will__ +9"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Hardness__ 10; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 10)"
    desc: "  Like normal objects, a giant animated statue has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once a giant animated statue is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 22."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stone Fist"
    desc: "+19 (magical)\n__Damage__  2d12 + 6 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Spar"
    desc: "+15 (magical, range increment 80 feet)\n__Damage__  4d6 + 6 piercing"

  - name: "Burn Alive"
    desc: "`pf2:1` (fire) The statue grinds a creature it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] into the red-hot coals of its brazier. The target takes 3d8 fire damage and 1d8 persistent fire damage."

  - name: "Splinter"
    desc: "`pf2:r`  **Trigger** A creature critically hits a timber titan\n* * *\n\n**Effect** The timber titan makes a spar Strike against a creature within 30 feet. This attack ignores any reactions triggered by making ranged attacks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Timber Titan
creatures:
  - 1: Timber Titan
```


Variant giant animated statue

Giant animated statues' increased size and power make them most useful in large vaults, spacious chambers, or outdoor locations. Tasks beyond their capabilities typically require a more advanced construct, not an animated object.

* * *

Granted a semblance of life through the use of rituals or other strange magic, animated objects take many forms and serve a variety of uses. A few examples of typical animated objects are listed below. Many of these creatures serve as guardians, surprising unsuspecting adventurers when they suddenly attack. Others serve as idle distractions for the exceptionally rich, simple servants created to handle odd jobs, and the like.
