---
title: "Grippli Skirmisher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uzrQPXeFKf4eqHQj" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/grippli
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Grippli Skirmisher"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #170: Spoken on the Song Wind"
name: "Grippli Skirmisher"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[grippli]]
trait_03: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Grippli"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +10, Stealth: +12, Survival: +11, Thievery: +10"
abilityMods: [2, 4, 3, 0, 3, -1]
speed: 25 feet,  climb 20 feet
sourcebook: "_Pathfinder #170: Spoken on the Song Wind_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +14, __Will__ +9"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Kukri|Kukri]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Thieves' Toolkit|Thieves' Tools]], 30x [[Equipment/Arrows|Arrows]]"
  - name: "Springing Step"
    desc: "  When the skirmisher uses the Step action they ignore difficult terrain and may move up to 10 feet instead of 5 feet."

abilities_mid:
  - name: ""
  - name: "Hopping Dodge"
    desc: "`pf2:r`  **Trigger** A creature misses the skirmisher with a melee Strike\n* * *\n\n**Effect** The skirmisher quickly takes advantage of the attacker's error and Steps."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Kukri"
    desc: "+14 (agile, finesse, trip)\n__Damage__  1d6 + 4 slashing plus baneback-poison"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+14 (deadly d10, propulsive, range increment 60 feet, reload 0)\n__Damage__  1d6 + 3 piercing plus baneback-poison"

  - name: "Baneback Poison"
    desc: " (poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** 2d4 poison damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)\n\n**Stage 3** 2d4 poison damage, [[Conditions/Stupefied|Stupefied 3]], and [[Conditions/Off-Guard|Off-Guard]] (1 round)"

  - name: "Jungle Stride"
    desc: "  Gripplis ignore difficult terrain in forests and jungles."

  - name: "Wily Attack"
    desc: "  The skirmisher deals an extra 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures and creatures afflicted by a poison."
 
```

```encounter-table
name: Grippli Skirmisher
creatures:
  - 1: Grippli Skirmisher
```



Skirmishers are jittery baneback hunters or ambushers. Although they often fight in groups, they aren't loyal to each other and sometimes leave one member of the group behind to face punishment while the others flee.

* * *

Gripplis are small, frog-like humanoids native to tropical rainforests. Most gripplis live in tight-knit treetop villages and survive primarily as hunters and gatherers. While most communities are peaceful and harmonious, a lingering superstition has led to a unique group of these people being cut off from their communal bonds and forced to make their own way in the world.

Among the many gripplis who possess poison glands, a rare subset secrete mind-altering chemicals. These gripplis aren't immune to this toxin, and over many years it may render them erratic at best and selfishly misanthropic at worst. Other gripplis view these "banebacks" as cursed and react to their presence with fear and mistrust, which usually leads to their censure and exile. They soon find that their natural skills as hunters, combined with an unlimited supply of their potent toxin, make them ideally suited to taking on work as mercenaries, bandits, or assassins.
