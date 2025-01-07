---
title: "Animated Trebuchet"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3JNzalUAQVIiQ0iI" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Animated Trebuchet"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Animated Trebuchet"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [9, 2, 8, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 36
armorclass:
  - name: AC
    desc: "36 (32 when broken); construct armor; __Fort__ +29, __Ref__ +19, __Will__ +17"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Hardness__ 14; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 14)"
    desc: "  Like normal objects, an animated trebuchet has Hardness. This Hardness reduces any damage the trebuchet takes by an amount equal to the Hardness. Once an animated trebuchet is reduced to fewer than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 32."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm"
    desc: "+28 (magical, reach 15 feet)\n__Damage__  3d12 + 11 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+28 (brutal, magical, range increment 120 feet)\n__Damage__  3d10 + 11 bludgeoning"

  - name: "Launch"
    desc: "`pf2:1`  **Requirements** The animated trebuchet has a creature [[Conditions/Grabbed|Grabbed]] in its arm.\n* * *\n\n**Effect** The animated trebuchet attempts an Athletics check check against the grabbed creature's Fortitude DC.\n\nOn a success, it fires the creature up to 40 feet in height and up to 120 feet away. The creature takes 4d12 bludgeoning damage plus the appropriate falling damage. If the flung creature lands on another creature, the creature it lands on takes the same amount of bludgeoning damage (DC 33 Reflex check save).\n\nOn a successful Launch, the animated trebuchet must Interact to reposition its arm into the proper position before it can Launch again."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, arm, DC 33 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Animated Trebuchet
creatures:
  - 1: Animated Trebuchet
```



Large armies sometimes pay exorbitant fees to animate their siege weapons.

* * *

Many animated objects have useful functions but become dangers when uncontrolled.
