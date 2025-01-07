---
title: "Wereboar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.k4KQxUft2IQ9m3Vx" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Wereboar"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Wereboar"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[werecreature]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; boar empathy"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Intimidation: +5, Survival: +7"
abilityMods: [4, 1, 4, 0, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +5, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Dagger|Dagger]], [[Equipment/Studded Leather Armor|Studded Leather Armor]]"
  - name: "Boar Empathy"
    desc: " (primal) The wereboar can communicate with boars and pigs."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+10 (agile, versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "**Melee** `pf2:1` Tusk"
    desc: "+10 ()\n__Damage__  1d8 + 6 piercing plus curse-of-the-wereboar"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d4 + 6 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+7 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "Boar Charge"
    desc: "`pf2:2`  The wereboar Strides twice and then makes a melee Strike. As long as they moved at least 20 feet, they gain a +2 circumstance bonus to their attack roll."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The werecreature changes into their humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is their hybrid shape. In humanoid shape, the werecreature uses their original humanoid size, loses their jaws and claw Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by their claw. In animal shape, their Speed and size change to that of the animal, they gain any special Strike effects of the animal that they didn't already have (such as [[Bestiary Ability Glossary/Grab|Grab]]), and they lose their weapon Strikes.\n\nHuman with fist +10 for 1d4+2 bludgeoning damage, or [[Monster Core/Boar|Boar]] with Speed 40 feet and tusk for 2d6+4 piercing damage.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Curse of the Wereboar"
    desc: " (curse,primal) This curse affects only humanoids\n\n**Saving Throw** DC 15 Fortitude check.\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into a wearboar until dawn. The creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws Strike (or a similar Strike) by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"
 
```

```encounter-table
name: Wereboar
creatures:
  - 1: Wereboar
```



Wereboars tend to be aggressive and stubborn, and often live with their own kind in small, remote communities. Even when they're inclined to interact with others, wereboars' short tempers and hostile nature lead other creatures to avoid them. Lone wereboars who settle down-often on remote farms-are extremely territorial, though others are content to roam and explore lands far from home. Their other habits also vary widely from individual to individual, right down to diet: some wereboars might feast on human flesh, while others are mostly vegetarian.
