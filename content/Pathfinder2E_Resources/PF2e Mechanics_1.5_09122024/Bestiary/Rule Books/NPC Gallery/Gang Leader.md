---
title: "Gang Leader"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y11mwI4CWtkQ8cWX" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Gang Leader"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Gang Leader"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +13, Deception: +15, Intimidation: +17, Society: +11, Stealth: +13, Thievery: +15, Underworld Lore: +15"
abilityMods: [4, 4, 2, 2, -1, 4]
speed: 30 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +17, __Will__ +10"
hp: 104
health:
  - name: ""
  - name: HP
    desc: "104"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortsword|+1 Shortsword]], [[Equipment/Sling|Sling]], [[Equipment/Glue Bomb (Moderate)|Tanglefoot Bag (Moderate)]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Healing Potion (Minor)|Healing Potion (Minor)]], 10x [[Equipment/Sling Bullets|Sling Bullets]]"
abilities_mid:
  - name: ""
  - name: "Deny Advantage"
    desc: "  The gang leader isn't [[Conditions/Off-Guard|Off-Guard]] to creatures of 7th level or lower that are [[Conditions/Hidden|Hidden]], [[Conditions/Undetected|Undetected]], flanking, or using surprise attack."

  - name: "Evasion"
    desc: "  When the gang leader rolls a success on a Reflex save, they get a critical success instead."

  - name: "Nimble Dodge"
    desc: "`pf2:r`  **Trigger** The gang leader is targeted with an attack by an attacker they can see\n* * *\n\n**Effect** The gang leader gains a +2 circumstance bonus to AC against the triggering attack."

  - name: "Surprise Attack"
    desc: "  On the first round of combat, if the gang leader rolls Deception or Stealth for initiative, creatures who haven't acted are [[Conditions/Off-Guard|Off-Guard]] to the gang leader."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+18 (agile, magical, versatile s)\n__Damage__  1d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+18 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d6 + 8 bludgeoning"

  - name: "Brutal Rally"
    desc: "`pf2:r` (auditory,emotion,linguistic,mental) **Trigger** The gang leader rolls a critical hit against a creature\n* * *\n\n**Effect** All allies that can see the gang leader gain a +1 circumstance bonus to attack rolls until the start of the gang leader's next turn.\n\n[[Bestiary Effects/Effect_ Brutal Rally|Effect: Brutal Rally]]"

  - name: "Gang Up"
    desc: "  Any enemy is [[Conditions/Off-Guard|Off-Guard]] against the gang leader's melee attacks due to flanking as long as the enemy is within melee reach of both the gang leader and one of the gang leader's allies."

  - name: "Quick Draw"
    desc: "`pf2:1`  The gang leader [[Actions/Interact|Interacts]] to draw a weapon, then Strikes with that weapon."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The gang leader deals an extra 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Gang Leader
creatures:
  - 1: Gang Leader
```



Cutthroats, killers, thieves, and toughs prey upon the vulnerable of society. Directing their activities and keeping them in line are the duties of the gang leader.

* * *

Villains pursue selfish and cruel goals, trampling over anyone foolish or purehearted enough to stand in their way.
