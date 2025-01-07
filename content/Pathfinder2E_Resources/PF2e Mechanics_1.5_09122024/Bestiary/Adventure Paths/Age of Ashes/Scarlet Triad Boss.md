---
title: "Scarlet Triad Boss"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LnX7DRH3ir4GyIIG" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Scarlet Triad Boss"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Scarlet Triad Boss"
level: "Creature 17"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; "
languages: "Common, Kelish, Kholo, Osiriani"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Deception: +29, Diplomacy: +27, Intimidation: +31, Society: +28, Stealth: +30, Thievery: +33"
abilityMods: [6, 9, 5, 7, 5, 4]
speed: 30 feet
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +27, __Ref__ +33, __Will__ +29"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+2 Greater Striking Composite Shortbow]], [[Equipment/Shortsword|+2 Striking Shortsword]], [[Equipment/Studded Leather Armor|+2 Resilient Studded Leather Armor]], [[Equipment/Thieves' Toolkit (Infiltrator)|Thieves' Tools (Infiltrator)]], [[Equipment/Weeping Midnight|Weeping Midnight (applied to one arrow)]]"
abilities_mid:
  - name: ""
  - name: "Return Fire"
    desc: "`pf2:r`  **Trigger** The Scarlet Triad boss is the target of a physical ranged attack\n* * *\n\n**Effect** They gain a +4 circumstance bonus to AC against the triggering attack. If the attack misses and the boss has their shortbow in hand, the boss Strikes the attacker with their shortbow."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+34 (agile, finesse, versatile s)\n__Damage__  2d6 + 12 piercing"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+34 (deadly 2d10, range increment 60 feet, reload 0)\n__Damage__  3d6 + 9 piercing"

  - name: "Darting Shot"
    desc: "`pf2:2`  The Scarlet Triad boss Feints a target, Strides up to their Speed, and makes a Strike with their shortbow in any order. They can Feint any target within 30 feet when using this ability."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The scarlet triad boss deals 4d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Scarlet Triad Boss
creatures:
  - 1: Scarlet Triad Boss
```




