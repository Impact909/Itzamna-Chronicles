---
title: "Starving Werebat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w5R6DtxFDGO45yXe" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Starving Werebat"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Starving Werebat"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[gnome]]
trait_04: [[humanoid]]
trait_05: [[werecreature]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; bat empathy"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +4, Deception: +2, Society: +3, Stealth: +6"
abilityMods: [2, 4, 3, 1, 3, 0]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +7, __Ref__ +8, __Will__ +5"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Dagger|Dagger]], [[Equipment/Studded Leather Armor|Studded Leather Armor]]"
  - name: "Bat Empathy"
    desc: " (primal) A werebat can communicate with bats."

abilities_mid:
  - name: ""
  - name: "Wing Thrash"
    desc: "`pf2:r`  **Trigger** An adjacent enemy damages the werebat\n* * *\n\n**Effect** The werebat makes one or two wing Strikes, each against a different adjacent creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+10 (finesse)\n__Damage__  1d8 + 2 slashing plus werecreature-curse-of-the-werecreature"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+10 (agile, finesse)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+10 (agile, finesse, versatile s)\n__Damage__  1d4 + 2 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+10 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 2 piercing"

  - name: "[[Creature Family Ability Glossary/(Werecreature) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) *   **Human**\n    *   **Melee** fist +10/+6/+2 (agile, nonlethal), **Damage** 1d4+2 bludgeoning damage\n    *   **Speed** 25 feet\n*   **Giant Bat**\n    *   **Speed** 15 feet, fly 30 feet\n* * *\n\nThe werecreature changes into its humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is its hybrid shape.\n\nIn humanoid shape, the werecreature uses its original humanoid size, loses its jaws and claws Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by its claw.\n\nIn animal shape, its Speed and size change to that of the animal, it gains any special Strike effects of the animal that it didn't already have (such as Grab), and it loses its weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Werebat]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 15 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into a werecreature until dawn. The creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws Strike (or a similar Strike) by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"
 
```

```encounter-table
name: Starving Werebat
creatures:
  - 1: Starving Werebat
```


Weak svirfneblin werebat

Werebats form organized colonies of opportunistic hunters. They aren't shy about transforming creatures to add to their colony, whom they initiate with elaborate social ceremonies and bloody hazing. The curse of the werebat gives them a strong urge to prey upon on weaker, lonely creatures. True werebats are often unusually tall and thin, with angular features. In combat, werebats favor their unarmed attacks because they can't fly while wielding weapons in their wings.

* * *

Werecreatures are humanoids who transform into animals and animal-humanoid hybrids under the light of the full moon. The fate of these shapechanging creatures derives from an ancient primal curse that they can, in turn, transmit through their own bites. The stat blocks in this section reflect werecreatures in their hybrid forms.
