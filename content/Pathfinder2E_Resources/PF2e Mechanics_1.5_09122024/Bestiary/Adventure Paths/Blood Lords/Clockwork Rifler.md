---
title: "Clockwork Rifler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qptFdCrLU1fhRmB5" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Clockwork Rifler"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Clockwork Rifler"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [5, 3, 4, -5, 4, -5]
speed: 25 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +15, __Will__ +12"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 5, orichalcum 5; __Resistances__ physical 5 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Double-Barreled Musket|+1 Striking Double-Barreled Musket]], [[Equipment/Bayonet|Bayonet]], 10x [[Equipment/Rounds (Double-Barreled Musket)|Rounds (Double-Barreled Musket)]]"
  - name: "Wind-Up"
    desc: "  24 hours, DC 22 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to [[Actions/Disable a Device|Disable a Device]] to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bayonet"
    desc: "+17 (agile, finesse, reach 10 feet)\n__Damage__  1d4 + 9 piercing"

  - name: "**Ranged** `pf2:1` Double-Barreled Musket"
    desc: "+18 (concussive, double barrel, fatal d10, range increment 60 feet, reload 1)\n__Damage__  2d6 + 9 piercing"

  - name: "Bayonet Charge"
    desc: "`pf2:2`  The clockwork rifler Strides twice and Strikes with its bayonet."
 
```

```encounter-table
name: Clockwork Rifler
creatures:
  - 1: Clockwork Rifler
```


Variant clockwork soldier

These diligent machines guard their assigned posts tirelessly. A typical clockwork soldier stands 6 feet tall and consists of 500 pounds of metal and magic.

* * *

Intricate, complex machines, clockworks are built with care by highly skilled engineers. Though their creation involves some amount of magic, they're primarily mechanical, packed with precision-tuned gears and springs working in concert.

The sturdy mainspring within a clockwork must be wound to provide the energy needed to power the device. Some larger clockworks contain a series of springs for different limbs that each need to be wound. A clockwork's crafter creates a unique metal key while building the clockwork; winding the clockwork usually involves inserting the key into the machine's back and turning clockwise. Larger clockworks require greater strength to turn the key, and typically have larger keys to allow for more torque-some even accommodating a team of winders rather than an individual. Programming a clockwork requires both the key and the knowledge to set the program correctly, information usually reserved for the clockwork's creator or owner.
