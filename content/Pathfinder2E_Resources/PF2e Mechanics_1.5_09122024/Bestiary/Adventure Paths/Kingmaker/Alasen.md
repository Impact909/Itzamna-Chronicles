---
title: "Alasen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CNVjcebUOWxVuMG6" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Alasen"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Alasen"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[werecreature]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common; tiger empathy"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +28, Stealth: +25, Survival: +21, Thievery: +25, Warfare Lore: +20"
abilityMods: [8, 6, 5, 0, 6, 5]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +23, __Ref__ +28, __Will__ +26"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245; __Weaknesses__ silver 10; __Resistances__ cold 5, fire 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Leather Armor|+1 Resilient Greater Invisibility Leather Armor]], [[Equipment/Charm of Resistance|Ring of Energy Resistance (Fire)]], [[Equipment/Charm of Resistance|Ring of Energy Resistance (Cold)]]"
  - name: "Tiger Empathy"
    desc: " (primal) Alasen can communicate with felines."

abilities_mid:
  - name: ""
  - name: "Defensive Roll"
    desc: "`pf2:0`  **Frequency** once per 10 minutes\n\n**Trigger** A physical attack would reduce Alasen to 0 Hit Points.\n* * *\n\n**Effect** Alasen drops into a roll to disperse the force of the blow and takes half damage from the attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 ()\n__Damage__  3d6 + 16 piercing plus werecreature-curse-of-the-werecreature"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile)\n__Damage__  3d4 + 16 slashing"

  - name: "[[Creature Family Ability Glossary/(Werecreature) Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) Medium human with fist +26 for 2d6+16 bludgeoning, or tiger with Speed 30 feet and Wrestle.\n\nWrestle `pf2:1` The tiger makes a claw Strike against a creature it is grabbing. If the attack hits, that creature is knocked [[Conditions/Prone|Prone]].\n* * *\n\nThe werecreature changes into its humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true werecreature's natural form is its hybrid shape.\n\nIn humanoid shape, the werecreature uses its original humanoid size, loses its jaws and claws Strikes, and gains a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by its claw.\n\nIn animal shape, its Speed and size change to that of the animal, it gains any special Strike effects of the animal that it didn't already have (such as Grab), and it loses its weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Critical Debilitating Strike"
    desc: "  **Trigger** Alasen's Strike hits an [[Conditions/Off-Guard|Off-Guard]] creature and deals damage.\n* * *\n\n**Effect** The target becomes [[Conditions/Enfeebled|Enfeebled 1]] or takes a -10-foot status penalty to its Speeds, as chosen by Alasen. On a critical hit, the target must also attempt a DC 34 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Slowed|Slowed 1]] until the end of Alasen's next turn.\n\n**Failure** The target is [[Conditions/Slowed|Slowed 2]] until the end of Alasen's next turn.\n\n**Critical Failure** The target is [[Conditions/Paralyzed|Paralyzed]] until the end of Alasen's next turn."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Weretiger]]"
    desc: " (curse,primal) This curse affects only humanoids.\n* * *\n\n**Saving Throw** DC 34 Fortitude check\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into the same kind of werecreature until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling unconscious until dawn."

  - name: "Mobility"
    desc: "  When Alasen takes a Stride action to move half her Speed or less, that movement does not trigger reactions."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the werecreature must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of its jaws Strike (or a similar Strike) by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Pounce"
    desc: "`pf2:1`  The weretiger Strides and makes a Strike at the end of that movement. If the weretiger began this action [[Conditions/Hidden|Hidden]], they remain hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  Alasen deals 2d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Alasen
creatures:
  - 1: Alasen
```


Female human weretiger


