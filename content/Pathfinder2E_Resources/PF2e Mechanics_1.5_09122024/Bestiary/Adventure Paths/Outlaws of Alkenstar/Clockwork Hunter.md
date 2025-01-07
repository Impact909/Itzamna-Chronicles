---
title: "Clockwork Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zijft0YUhPYgwHMU" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Clockwork Hunter"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Clockwork Hunter"
level: "Creature 0"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +4, Stealth: +8"
abilityMods: [0, 4, 0, -5, 3, -5]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +2, __Ref__ +8, __Will__ +5"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 2, orichalcum 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "10x [[Equipment/Bolts|Bolts]]"
  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  48 hours, DC 14 Thievery check check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Leg"
    desc: "+8 (agile, finesse)\n__Damage__  1d4 bludgeoning"

  - name: "**Ranged** `pf2:1` Crossbow Bolt Launcher"
    desc: "+8 (range 60 feet, reload 1)\n__Damage__  1d6 piercing"

  - name: "Salvage Ammunition"
    desc: "`pf2:2`  The clockwork hunter gathers up any unattended crossbow bolts within reach and reloads its bolt launcher. The hunter restocks its supply of bolts, up to 10 bolts maximum."

  - name: "Skirmish Strike"
    desc: "`pf2:1`  The clockwork hunter shuffles its feet and its weapon in tandem. It either Steps and then Strikes, or Strikes and then Steps."

  - name: "Target Weakness"
    desc: "`pf2:2`  The clockwork hunter takes a moment to scan a creature for weaknesses, then Strikes with a +1 circumstance bonus to its attack roll. The hunter's Strike gains the deadly d4 trait for this attack."
 
```

```encounter-table
name: Clockwork Hunter
creatures:
  - 1: Clockwork Hunter
```



Clockwork creatures are as common in Alkenstar as carts and horses are in most Inner Sea region cities. In the City of Smog, clockworks perform many of the simple, repetitive tasks that sentient workers find boring, as well as dangerous jobs such as private security or riot control.

Tasks like patrolling the sewers for vermin are mundane, perfect for the clockwork hunter. Its hound-like appearance mimics one of humanity's trustiest hunting companions-with a few choice modifications, of course. Few hunting dogs, for example, sport sturdy metal plating and an integrated crossbow bolt launcher. Over time, clockwork makers have unofficially adopted a common model for the hunter, making it fairly easy to find spare parts or compatible accessory modules.

The city of Alkenstar owns a few dozen clockwork hunters for the purpose of keeping sewer tunnels free of vermin. Shieldmarshals sometimes drop boxes of extra crossbow bolts just inside sewer entrances, enabling clockwork hunters to resupply as needed.

Other businesses that tend to purchase clockwork hunters include warehouses, butchers, and bakers-essentially, anywhere rats and other vermin tend to congregate. Though quick, a clockwork hunter's body isn't very sturdy and tends to fall apart after only minor abuse. Elite clockwork hunters are fitted with specialty armored plating, giving them resistance 2 to physical damage (except adamantine or orichalcum).
