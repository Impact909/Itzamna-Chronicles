---
title: "Innkeeper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nftqo6ZVQtzkLVZU" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Innkeeper"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Innkeeper"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Deception: +6, Diplomacy: +8, Society: +7, Accounting Lore: +5, Cooking Lore: +5"
abilityMods: [2, 0, 1, 2, 2, 3]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +6, __Ref__ +3, __Will__ +9"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|Broom]], [[Equipment/Leather Armor|Innkeeper's Apron]], [[Equipment/Basic Crafter's Book|Ledger]]"
  - name: "Font of Gossip"
    desc: "  The inkeeper's business gives them insight into the neighborhood's happenings. When [[Actions/Gather Information|Gathering Information]], a person can gain as much information chatting with the innkeeper for 30 minutes to an hour as they would gain from 2 hours spent canvassing the neighborhood. Each person can learn gossip from an innkeeper only once per day, and only if the innkeeper is friendly or helpful to that individual.\n\nWhatever information the innkeeper knows about a given topic doesn't change if someone else asks the innkeeper about that topic, unless the innkeeper has since learned more."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Broom"
    desc: "+7 (two-hand d8)\n__Damage__  1d4 + 2 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal)\n__Damage__  1d4 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Ledger"
    desc: "+5 (nonlethal, thrown 10 ft.)\n__Damage__  1d4 + 2 bludgeoning"

  - name: "Home Turf"
    desc: "  An innkeeper gains a +2 circumstance bonus to attack rolls, damage rolls, and AC within their inn."
 
```

```encounter-table
name: Innkeeper
creatures:
  - 1: Innkeeper
```



The sight of an inn is a welcome one to any weary traveler. Innkeepers can often be found cleaning the common room, overseeing the evening meal, or settling in new lodgers. Innkeepers keep an eye on their neighbors' doings and are often excellent sources of information.

* * *

Countless adventures begin in a tavern or a pub. Maybe it's because such places attract the risk-prone, or maybe it's because everyone needs a little liquid courage before they decide to take on a group of rampaging ogres.
