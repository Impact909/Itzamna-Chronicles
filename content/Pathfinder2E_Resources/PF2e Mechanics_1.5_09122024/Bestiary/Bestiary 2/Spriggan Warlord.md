---
title: "Spriggan Warlord"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.srKdKWtbkFhy8ZU5" 
tags:
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/spriggan
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Spriggan Warlord"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Spriggan Warlord"
level: "Creature 7"

alignment: ""
size: "Small"
trait_01: [[gnome]]
trait_02: [[humanoid]]
trait_03: [[spriggan]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Intimidation: +17, Society: +12, Stealth: +17, Survival: +14, Thievery: +15"
abilityMods: [6, 4, 4, 1, 3, 4]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +17, __Will__ +14"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|+1 Crossbow]], [[Equipment/Morningstar|+1 Morningstar]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Enraged Growth"
    desc: "`pf2:r` (polymorph,primal) **Trigger** The spriggan warlord takes damage\n* * *\n\n**Effect** The spriggan warlord grows to size Large, along with their equipment (which returns to natural size if removed). The spriggan warlord's reach increases by 5 feet. They regain 15 healing Hit Points and gain a +2 status bonus to melee attack and damage rolls.\n\nThis effect continues until the end of the spriggan warlord's next turn, but on any turn in which the spriggan warlord deals damage to another creature and is not [[Conditions/Fatigued|Fatigued]], the effect extends until the end of the following turn.\n\nWhen Enraged Growth ends, the spriggan warlord is fatigued for 1 hour."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Morningstar"
    desc: "+18 (magical, versatile p)\n__Damage__  2d6 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+18 (magical, range increment 120 feet, reload 0)\n__Damage__  2d8 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +15; __4th __  _[[Spells/Fly|Fly]]_, _[[Spells/Shatter|Shatter]]_; __3rd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Fear|Fear]]_; __2nd __  _[[Spells/Blur|Blur]]_\n__Cantrips__  __(4th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "Bully's Bludgeon"
    desc: "`pf2:1` (nonlethal) The spriggan warlord makes a morningstar Strike with a +2 circumstance bonus to its attack roll. This attack is nonlethal."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The spriggan warlord's Strikes deal an additional 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Warlord's Training"
    desc: "  A spriggan warlord has access to the critical specialization effects for crossbows and morningstars, and the reload of any crossbow they wield is reduced by 1 (to a minimum of 0)."
 
```

```encounter-table
name: Spriggan Warlord
creatures:
  - 1: Spriggan Warlord
```



While the leaders of larger spriggan enclaves tend to be uniquely trained warriors with highly specialized skills, spriggan warlords are fond of the traditional spriggan weaponry of morningstar and crossbow, valuing this traditional fighting style for its simplicity and for using both weapons to their full potential. Spriggan warlords often serve as sub-commanders in large groups, filling roles in spriggan society akin to captains of the guard or bodyguards to spriggan royalty. In smaller groups or remote outposts, a single spriggan warlord is typically in charge of a band of spriggan bullies.
