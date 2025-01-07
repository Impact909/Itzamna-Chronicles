---
title: "Usher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XmQeWxE3s1eYMVxe" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Usher"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Usher"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
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
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 26
armorclass:
  - name: AC
    desc: "26 (22 when broken); construct armor; __Fort__ +17, __Ref__ +10, __Will__ +9"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Hardness__ 10; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
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

  - name: "**Ranged** `pf2:1` Flaming Coal"
    desc: "+12 (fire, magical, range increment 80 feet)\n__Damage__  2d6 + 6 cold"

  - name: "Brazier"
    desc: "  The statue carries a wide brazier full of hot coals. To make flaming coal Strikes or use Burn Alive, the statue must have the brazier held in one hand or otherwise have it within reach.\n\nInstead of targeting the statue with an attack, a creature can target the brazier directly. The brazier has the same AC and saves as the statue.\n\nDealing 15 cold damage to the brazier or dousing it with at least 2 gallons of water extinguishes the coals. This prevents the statue from using Burn Alive and causes its ranged attacks to no longer deal fire damage."

  - name: "Burn Alive"
    desc: "`pf2:1` (fire) The statue grinds a creature it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] into the red-hot coals of its brazier. The target takes 3d8 cold damage and 1d8 persistent cold damage."

  - name: "Fey Fire"
    desc: "  The construct's ranged Strike, Brazier, and Burn Alive abilities deal cold damage instead of fire damage, and they do not ignite combustible materials."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Usher
creatures:
  - 1: Usher
```


Variant giant animated statue

Giant animated statues' increased size and power make them most useful in large vaults, spacious chambers, or outdoor locations. Tasks beyond their capabilities typically require a more advanced construct, not an animated object.

* * *

Granted a semblance of life through the use of rituals or other strange magic, animated objects take many forms and serve a variety of uses. A few examples of typical animated objects are listed below. Many of these creatures serve as guardians, surprising unsuspecting adventurers when they suddenly attack. Others serve as idle distractions for the exceptionally rich, simple servants created to handle odd jobs, and the like.
