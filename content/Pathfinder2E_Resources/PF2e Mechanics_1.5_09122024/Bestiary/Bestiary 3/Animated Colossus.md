---
title: "Animated Colossus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WsuXKLuDxPfwlz4U" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Animated Colossus"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Animated Colossus"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +33"
abilityMods: [9, 2, 8, -5, 0, -5]
speed: 50 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 39
armorclass:
  - name: AC
    desc: "39 (35 when broken); construct armor; __Fort__ +31, __Ref__ +21, __Will__ +19"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245; __Hardness__ 15; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 15)"
    desc: "  Like normal objects, an animated colossus has Hardness. This Hardness reduces any damage the colossus takes by an amount equal to the Hardness. Once an animated colossus is reduced to fewer than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 35."

  - name: "Enormous"
    desc: "  An animated colossus takes up a space of 6 squares by 6 squares (30 feet by 30 feet) and is 100 feet tall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+32 (magical, reach 30 feet)\n__Damage__  3d12 + 17 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+32 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 17 bludgeoning"

  - name: "Colossus's Grasp"
    desc: "  The colossus can [[Bestiary Ability Glossary/Grab|Grab]] a creature using only one hand.\n\nIt can move normally with a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its fist, carrying the creature along. If it has two creatures grabbed in this way, it can't use its fist Strike."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d12+11 bludgeoning, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 36 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Animated Colossus
creatures:
  - 1: Animated Colossus
```



Animating a 100-foot-tall statue is worth the cost for spellcasters guarding immense dungeons.

* * *

Many animated objects have useful functions but become dangers when uncontrolled.
