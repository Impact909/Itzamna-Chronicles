---
title: "Wererat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HYUhLQsVFqij4qKV" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Wererat"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Wererat"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[werecreature]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; Rat Empathy"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +6, Deception: +5, Society: +4, Stealth: +8"
abilityMods: [2, 4, 2, 0, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +10, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Bolts|Bolts]]"
  - name: "[[Creature Family Ability Glossary/(Werecreature) Animal Empathy|Rat Empathy]]"
    desc: "  The wererat can communicate with rodents.\n* * *\n\nThe werecreature can ask questions of, receive answers from, and use the Diplomacy skill with animals of its general kind."

abilities_mid:
  - name: ""
  - name: "Nimble Dodge"
    desc: "`pf2:r`  **Trigger** A creature targets the wererat with an attack and the wererat can see the attacker;\n* * *\n\n**Effect** The wererat gains a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+10 (agile, finesse, versatile s)\n__Damage__  1d6 + 4 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile, finesse)\n__Damage__  1d6 + 2 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (finesse)\n__Damage__  1d8 + 2 piercing plus werecreature-curse-of-the-werecreature"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+10 (range increment 60 feet, reload 1)\n__Damage__  1d6 piercing"

  - name: "[[Creature Family Ability Glossary/(Werecreature) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) *   **Human**\n    *   **Melee** fist +10 **Damage** 1d4+2 bludgeoning\n*   **Rat**\n    *   **Size** small\n    *   **Speed** 30 feet, climb 10 feet\n* * *\n\nThe werecreature changes into its humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is its hybrid shape.\n\nIn humanoid shape, the werecreature uses its original humanoid size, loses its jaws and claws Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by its claw.\n\nIn animal shape, its Speed and size change to that of the animal, it gains any special Strike effects of the animal that it didn't already have (such as Grab), and it loses its weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Wererat]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 15 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into the same kind of werecreature until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Sneak Attack"
    desc: "  The wererat deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Wererat
creatures:
  - 1: Wererat
```



Wererats tend to be selfishly opportunistic, avaricious, and paranoid as a result of their curse. Because wererats typically dwell in metropolitan areas where they can hide in plain sight, practically any city goer could be a wererat in disguise—from the quiet shopkeep to the city's criminal mastermind. The bustle of crowds and countless rat holes make ghettos and shantytowns favored homes for wererats, especially since in these poorer districts the wererat can kill out of greed or fear with little chance of the authorities noticing. In some cities, wererats operate entire thieves' guilds or organized crime rings, and membership requires willfully submitting to the wererat's cursed bite. Wererats look very similar to ratfolk when in hybrid form, apart from potential differences in size, but ratfolk have no love for wererats.

* * *

Werecreatures are humanoids doomed to transform into animals and animalhumanoid hybrids under the light of the full moon. These shapechanging creatures are the result of an ancient primal curse that they can, in turn, transmit through their own bites. Their ability to lurk unseen in the wilds as well as among people, combined with the contagiousness of their condition, makes werecreatures a perennial cause of panicked suspicion.
