---
title: "Clockwork Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dXZCHDPeyLRJmzrV" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Clockwork Mage"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Clockwork Mage"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17"
abilityMods: [2, 6, 4, -5, 2, -5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +19, __Will__ +17"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 10, orichalcum 10; __Resistances__ physical 5 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Magic Wand (2nd-Rank Spell)|Clockwork Wand]]"
  - name: "Wind-Up"
    desc: "  24 hours, DC 26 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to [[Actions/Disable a Device|Disable a Device]] to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Clockwork Wand"
    desc: "  The clockwork mage uses a mechanical wand as a focus to channel magical energy. This wand is built into the clockwork mage's chest, with only the crystal at the end exposed. The mage can Interact to the remove the wand, or someone else can remove it with a DC 31 Thievery check check to [[Actions/Disable a Device|Disable a Device]]. The clockwork mage becomes unable to cast any spells except cantrips while the wand is removed.\n\nWhen removed, the clockwork wand is a _[[Equipment/Magic Wand (2nd-Rank Spell)|Magic Wand]]_ containing the last 2nd-rank innate spell the clockwork mage cast (the GM determines the spell randomly if it has not cast any eligible spells). The spells are placed within the wand while the mage is created, and the creator can substitute other arcane spells of the appropriate rank."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+19 (agile, finesse)\n__Damage__  2d10 + 6 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Cone of Cold|Cone of Cold]]_; __4th __  _[[Spells/Flicker|Blink]]_, _[[Spells/Fly|Fly]]_, _[[Spells/Wall of Fire|Wall of Fire]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Mist|Obscuring Mist]]_, _[[Spells/Web|Web]]_; __1st __  _[[Spells/Gentle Landing|Feather Fall]]_, _[[Spells/Carryall|Floating Disk]]_, _[[Spells/Grease|Grease]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Energize Clockwork Wand"
    desc: "`pf2:1` (concentrate) **Frequency** once per 10 minutes.\n* * *\n\n**Effect** The clockwork mage regains a spell it has already cast that day. It must spend 1 hour of its operational time, or 2 hours if the spell is 3rd rank or higher."
 
```

```encounter-table
name: Clockwork Mage
creatures:
  - 1: Clockwork Mage
```



A clockwork mage is a lethal blend of magic and machinery. Each of these clockworks is imbued with an arcane stone at its core that powers spells through the wand embedded in its chest.

* * *

Intricate, complex machines, clockworks are built with care by highly skilled engineers. Though their creation involves some amount of magic, they're primarily mechanical, packed with precision-tuned gears and springs working in concert.

The sturdy mainspring within a clockwork must be wound to provide the energy needed to power the device. Some larger clockworks contain a series of springs for different limbs that each need to be wound. A clockwork's crafter creates a unique metal key while building the clockwork; winding the clockwork usually involves inserting the key into the machine's back and turning clockwise. Larger clockworks require greater strength to turn the key, and typically have larger keys to allow for more torque-some even accommodating a team of winders rather than an individual. Programming a clockwork requires both the key and the knowledge to set the program correctly, information usually reserved for the clockwork's creator or owner.
