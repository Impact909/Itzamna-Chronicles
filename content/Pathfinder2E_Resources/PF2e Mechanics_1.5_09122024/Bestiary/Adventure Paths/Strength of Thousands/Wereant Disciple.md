---
title: "Wereant Disciple"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iF7frLwXF6QngrzJ" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/werecreature
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Wereant Disciple"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Wereant Disciple"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[lawful]]
trait_06: [[werecreature]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common; insect empathy, telepathy 120 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +28, Stealth: +29, Survival: +28"
abilityMods: [6, 9, 5, 0, 6, 4]
speed: 40 feet,  fly 60 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +28, __Ref__ +30, __Will__ +25"
hp: 305
health:
  - name: ""
  - name: HP
    desc: "305; __Weaknesses__ silver 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 120 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Animal Empathy|Insect Empathy]]"
    desc: " (primal) The wereant can communicate with insects."

abilities_mid:
  - name: ""
  - name: "Gnawing Retort"
    desc: "`pf2:r`  **Trigger** A creature adjacent to the wereant critically misses the wereant with a melee Strike\n* * *\n\n**Effect** The wereant makes a mandibles Strike against the triggering creature."

  - name: "Hive Mind"
    desc: " (primal) Wereants operate with a shared hive intelligence. While within telepathic range of at least one other wereant, a wereant disciple gains a +2 circumstance bonus to initiative checks, Perception checks, and saving throws against mental effects. If one wereant is aware of a combatant, all members of the hive mind within telepathic range are aware of it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+29 ()\n__Damage__  3d10 + 14 slashing plus werecreature-curse-of-the-werecreature"

  - name: "**Melee** `pf2:1` Carapace Fist"
    desc: "+32 (agile, finesse)\n__Damage__  3d8 + 14 bludgeoning plus staggering-blow"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The wereant changes into their humanoid, hybrid, or animal shape. Each shape has a specific, persistent appearance. A true wereant's natural form is their hybrid shape. In humanoid shape, they use their original humanoid size, lose their jaws and claw Strikes, and gain a melee fist Strike that deals bludgeoning damage equal to the slashing damage dealt by their mandibles. In animal shape, they take the form of a Medium giant ant, gain a climb Speed of 20 feet, gain Grab on their mandibles Strike, and lose their weapon Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Curse of the Werecreature|Curse of the Wereant]]"
    desc: " (curse,primal) This curse affects only humanoids\n\n**Saving Throw** DC 34 Fortitude check.\n\nOn each full moon, the cursed creature must succeed at another Fortitude save or turn into a wereant until dawn.\n\nThe creature is under the GM's control and goes on a rampage for half the night before falling [[Conditions/Unconscious|Unconscious]] until dawn."

  - name: "Flying Leap"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The wereant disciple Flies and makes two Strikes against different targets at any point during that movement. These Strikes deal an additional 2d6 precision damage if the disciple is above the target. If the wereant began this action [[Conditions/Hidden|Hidden]], they remain hidden until after this ability's Strikes. Both attacks count toward the disciple's multiple attack penalty, but the penalty doesn't increase until after both Strikes."

  - name: "[[Creature Family Ability Glossary/(Werecreature) Moon Frenzy|Moon Frenzy]]"
    desc: " (polymorph,primal) When a full moon appears in the night sky, the wereant must enter hybrid form, can't Change Shape thereafter, becomes one size larger, increases its reach by 5 feet, and increases the damage of their mandibles Strike by 2.\n\nWhen the moon sets or the sun rises, the werecreature returns to humanoid form and is [[Conditions/Fatigued|Fatigued]] for 2d4 hours.\n\n[[Bestiary Effects/Effect_ Moon Frenzy|Effect: Moon Frenzy]]"

  - name: "Staggering Blow"
    desc: "  A creature damaged by the wereant disciple's carapace fist Strike must succeed at a DC 35 Fortitude check save or become [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 2]] on a critical failure). If the Strike is a critical hit, a creature that fails the save is also [[Conditions/Paralyzed|Paralyzed]] for 1 round."
 
```

```encounter-table
name: Wereant Disciple
creatures:
  - 1: Wereant Disciple
```



Insectile werecreatures, such as wereants, only come about in unusual circumstances, such as powerful curses from inhuman gods or transformative magic run amok. Wereants work together with a natural cohesion that's rare in other types of werecreatures. The wereants presented here are more powerful than most wereants, as they've been warped by the forces contained within the Vesicant Egg.

Some wereants have a religious zeal about training to protect their community and gladly give their lives for the hive.
