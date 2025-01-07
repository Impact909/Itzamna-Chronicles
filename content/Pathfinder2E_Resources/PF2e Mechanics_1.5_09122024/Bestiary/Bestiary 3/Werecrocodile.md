---
title: "Werecrocodile"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L90qrPxIbMAAqqY7" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Werecrocodile"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Werecrocodile"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[werecreature]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision"
languages: "Common; crocodile empathy"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +7, Stealth: +5"
abilityMods: [4, 1, 3, 0, 3, 1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +5, __Will__ +9"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55; __Weaknesses__ silver 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Hatchet|Hatchet]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "Crocodile Empathy"
    desc: " (primal) A werecrocodile can communicate with alligators, caimans, and crocodiles."

  - name: "Deep Breath"
    desc: "  A werecrocodile can hold their breath for about 2 hours."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 ()\n__Damage__  1d10 + 4 piercing plus werecreature-curse-of-the-werecreature,grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+10 (agile, sweep)\n__Damage__  1d6 + 4 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+7 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 4 slashing"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  30 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) *   **Human**\n    *   **Melee** fist +10/+6/+2 (agile, nonlethal), **Damage** 1d4+2 bludgeoning damage\n*   **Crocodile**\n    *   **Melee** jaws+10/+5/+0, **Damage** 2d6+4 piercing damage\n* * *\n\nThe werecreature changes into its humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is its hybrid shape.\n\nIn humanoid shape, the werecreature uses its original humanoid size, loses its jaws and claws Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by its claw.\n\nIn animal shape, its Speed and size change to that of the animal, it gains any special Strike effects of the animal that it didn't already have (such as Grab), and it loses its weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Werecrocodile]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 15 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into a werecrocodile until dawn. The creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws Strike (or a similar Strike) by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Twisting Thrash"
    desc: "`pf2:1`  **Requirements** The werecrocodile has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The werecrocodile makes a Jaws Strike with a +2 circumstance bonus to the attack roll against the grabbed creature. If this Strike hits, it also knocks the target [[Conditions/Prone|Prone]]. If it fails, the werecrocodile releases the target."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Werecrocodile
creatures:
  - 1: Werecrocodile
```



The curse of the werecrocodile instills powerful hunger, urges violent displays of dominance, and amplifies greed.

* * *

Werecreatures are humanoids who transform into animals and animal-humanoid hybrids under the light of the full moon. The fate of these shapechanging creatures derives from an ancient primal curse that they can, in turn, transmit through their own bites. The stat blocks in this section reflect werecreatures in their hybrid forms.
