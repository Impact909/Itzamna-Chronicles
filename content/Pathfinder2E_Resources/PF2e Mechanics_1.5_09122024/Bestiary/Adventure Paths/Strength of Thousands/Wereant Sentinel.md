---
title: "Wereant Sentinel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Q8O542nX7JHptKDG" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Wereant Sentinel"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Wereant Sentinel"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
trait_06: [[werecreature]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common; insect empathy, telepathy 120 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +37, Intimidation: +33, Society: +27"
abilityMods: [10, 5, 5, 0, 5, 6]
speed: 40 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 43
armorclass:
  - name: AC
    desc: "43 (45 with shield raised); __Fort__ +35, __Ref__ +29, __Will__ +32"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Weaknesses__ silver 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Khopesh|+2 Greater Striking Khopesh]], [[Equipment/Sturdy Shield (Major)|Sturdy Shield (Major)]]"
  - name: "[[Creature Family Ability Glossary/(Werecreature) Animal Empathy|Insect Empathy]]"
    desc: " (primal) The wereant can communicate with insects."

abilities_mid:
  - name: ""
  - name: "Gnawing Retort"
    desc: "  `pf2:r` As wereant disciple."

  - name: "Hive Mind"
    desc: " (primal) Wereants operate with a shared hive intelligence. While within telepathic range of at least one other wereant, a wereant disciple gains a +2 circumstance bonus to initiative checks, Perception checks, and saving throws against mental effects. If one wereant is aware of a combatant, all members of the hive mind within telepathic range are aware of it."

  - name: "Retributive Strike"
    desc: "`pf2:r`  **Trigger** An enemy damages the wereant sentinel's ally, and both are within 15 feet of the wereant sentinel\n* * *\n\n**Effect** The ally gains resistance 20 against the triggering damage. If the foe is within reach, the wereant sentinel makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+36 ()\n__Damage__  3d10 + 20 slashing plus werecreature-curse-of-the-werecreature,knockdown"

  - name: "**Melee** `pf2:1` Khopesh"
    desc: "+38 (magical, trip)\n__Damage__  3d8 + 20 slashing"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The wereant changes into their humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true wereant's natural form is their hybrid shape. In humanoid shape, they use their original humanoid size, lose their jaws and claw Strikes, and gain a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by their mandibles. In animal shape, they take the form of a Medium giant ant, gain a climb Speed of 20 feet, gain Grab on their mandibles Strike, and lose their weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Wereant]]"
    desc: " (curse,primal) This curse affects only humanoids\n\n**Saving Throw** DC 34 Fortitude check.\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into a wereant until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling [[Conditions/Unconscious|Unconscious]] until dawn."

  - name: "Hasty Reposition"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The wereant sentinel Steps, moving up to 15 feet."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the wereant must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of their mandibles Strike by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Sentinel's Focus"
    desc: "`pf2:1`  The wereant sentinel plants its feet in defiance of those who would move it. It gains a +2 circumstance bonus to defenses against being Shoved or Tripped, and its melee Strikes deal an additional 2d8 mental damage. These effects end when it moves from its square using anything other than Hasty Reposition."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Wereant Sentinel
creatures:
  - 1: Wereant Sentinel
```




