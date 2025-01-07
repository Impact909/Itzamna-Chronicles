---
title: "Werebear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.20qg9xNec2pvvf7d" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Werebear"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Werebear"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[werecreature]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; Bear Empathy"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Medicine: +9, Nature: +11, Stealth: +11, Survival: +11"
abilityMods: [5, 2, 4, 1, 3, -1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +10, __Will__ +10"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]], 8x [[Equipment/Hatchet|Hatchet]], [[Equipment/Chain Shirt|Chain Shirt]]"
  - name: "[[Creature Family Ability Glossary/(Werecreature) Animal Empathy|Bear Empathy]]"
    desc: "  The werebear can communicate with ursine creatures.\n* * *\n\nThe werecreature can ask questions of, receive answers from, and use the Diplomacy skill with animals of its general kind."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile, reach 10 feet)\n__Damage__  1d10 + 7 slashing plus grab"

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+13 (reach 10 feet, sweep)\n__Damage__  1d12 + 7 slashing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+13 (agile, sweep)\n__Damage__  1d6 + 7 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 (reach 10 feet)\n__Damage__  1d12 + 7 piercing plus werecreature-curse-of-the-werecreature"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+10 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 7 slashing"

  - name: "[[Creature Family Ability Glossary/(Werecreature) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) *   **Human**\n    *   **Size** Medium\n    *   **Melee** fist +13 **Damage** 1d4+7\n*   **Grizzly Bear**\n    *   **Speed** 35 feet\n* * *\n\nThe werecreature changes into its humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is its hybrid shape.\n\nIn humanoid shape, the werecreature uses its original humanoid size, loses its jaws and claws Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by its claw.\n\nIn animal shape, its Speed and size change to that of the animal, it gains any special Strike effects of the animal that it didn't already have (such as Grab), and it loses its weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Werebear]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 18 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into the same kind of werecreature until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) The werebear designates a single creature they can see and hear, or one they're Tracking, as their prey. The werebear gains a +2 circumstance bonus to Perception checks when they [[Actions/Seek|Seek]] their prey and to Survival checks when they [[Actions/Track|Track]] their prey. The first time the werebear hits the designated prey in a round, they deal an additional 1d8 precision damage. These effects last until the werebear uses Hunt Prey again."

  - name: "Mauler"
    desc: "  The werebear gains a +2 circumstance bonus to damage rolls against creatures it has [[Conditions/Grabbed|Grabbed]]."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Werebear
creatures:
  - 1: Werebear
```



Unwavering conviction fills a werebear during their transformations. This can drive them zealously into noble causes, but it can also make them ruthless, violent, and single-minded. Alliances can fall from a werebear's mind as their bestial temper overcomes them and their goal overwhelms all. As a result, werebears are loners, rarely even living together as families longer than necessary. As long as there is nothing around to threaten it or the natural area it protects (typically a forest), a werebear in its animal form is generally content to forage and sleep away the night.

* * *

Werecreatures are humanoids doomed to transform into animals and animalhumanoid hybrids under the light of the full moon. These shapechanging creatures are the result of an ancient primal curse that they can, in turn, transmit through their own bites. Their ability to lurk unseen in the wilds as well as among people, combined with the contagiousness of their condition, makes werecreatures a perennial cause of panicked suspicion.
