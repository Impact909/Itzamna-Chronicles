---
title: "Dwarven Monster Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6CWLRpzHARjgwy3Q" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Dwarven Monster Hunter"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Dwarven Monster Hunter"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[humanoid]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; "
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Stealth: +13, Survival: +11, Monster Lore: +13"
abilityMods: [4, 3, 3, 1, 1, 1]
speed: 15 feet
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +11, __Will__ +13"
hp: 108
health:
  - name: ""
  - name: HP
    desc: "108"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Greataxe|+1 Greataxe]], [[Equipment/Hide Armor|Hide Armor]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+15 (magical, sweep)\n__Damage__  1d12 + 8 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+14 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 6 piercing"

  - name: "Rage"
    desc: "`pf2:1` (concentrate,emotion,mental) **Requirements** The monster hunter isn't [[Conditions/Fatigued|Fatigued]] or raging\n* * *\n\n**Effect** The monster hunter gains 9 temporary Hit Points that last until the rage ends. While raging, they deal 8 additional damage with melee attacks, gain a +10-foot status bonus to their Speed, and take a -1 penalty to AC. The monster hunter can't use concentrate actions except [[Actions/Seek|Seek]] and rage actions.\n\nThe rage lasts for 1 minute, until there are no enemies the monster hunter can perceive, or until the monster hunter falls unconscious.\n\nOnce the rage ends, the monster hunter can't again for 1 minute.\n\n[[Feat_Feature Effects/Effect_ Rage|Effect: Rage]]"

  - name: "Sudden Charge"
    desc: "`pf2:2`  The monster hunter Strides twice and makes a melee Strike."
 
```

```encounter-table
name: Dwarven Monster Hunter
creatures:
  - 1: Dwarven Monster Hunter
```


Variant Monster Hunter

Some mercenaries eschew the complications of politics, oaths of service, and fealty and just get paid to hunt monsters. It's a straightforward form of mercenary service, often dangerous in the extreme, but one that can yield glory and fame.

* * *

A broad category that includes those wielding arms, spells, or even guile and cunning, mercenaries hire themselves and their expertise to those with the gold to pay for it.
