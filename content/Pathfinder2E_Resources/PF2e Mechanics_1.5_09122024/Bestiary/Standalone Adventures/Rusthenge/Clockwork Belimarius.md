---
title: "Clockwork Belimarius"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.J7r2Sv3NEmlcBCKZ" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Clockwork Belimarius"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Clockwork Belimarius"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +12"
abilityMods: [2, 4, 3, -5, 2, -5]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +12, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 5, orichalcum 5; __Resistances__ physical 5 (except adamantine, bludgeoning, or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|+1 Striking Halberd]], [[Equipment/Magic Wand (2nd-Rank Spell)|Clockwork Wand]]"
  - name: "Wind-Up"
    desc: "  24 hours, DC 21 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to [[Actions/Disable a Device|Disable a Device]] to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Clockwork Wand"
    desc: "  The clockwork mage uses a mechanical wand as a focus to channel magical energy. This wand is built into the clockwork mage's chest, with only the crystal at the end exposed. The mage can Interact to the remove the wand, or someone else can remove it with a DC 25 Thievery check check to [[Actions/Disable a Device|Disable a Device]]. The clockwork mage becomes unable to cast any spells except cantrips while the wand is removed.\n\nWhen removed, the clockwork wand is a _[[Equipment/Magic Wand (2nd-Rank Spell)|Magic Wand]]_ containing the last 1st-rank innate spell the clockwork mage cast ([[Spells/Fear|Fear]], if the clockwork Belimarius hasn't yet cast a 1st-rank spell in this adventure). The spells are placed within the wand while the mage is created, and the creator can substitute other arcane spells of the appropriate rank."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+16 (magical, reach 10 feet, versatile s)\n__Damage__  2d10 + 4 piercing plus dispelling-critical"

  - name: "Arcane Innate Spells"
    desc: "DC 21, attack +13; __2nd __  _[[Spells/Magnetic Repulsion|Magnetic Repulsion]]_, _[[Spells/Resist Energy|Resist Energy]]_; __1st __  _[[Spells/Dizzying Colors|Color Spray]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Mystic Armor|Mystic Armor]]_\n__Cantrips__  __(2nd)__ _[[Spells/Daze|Daze]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Dispelling Critical"
    desc: "  On a critical hit with a halberd Strike, shards of noqual built into the clockwork Belimarius glow green for a moment. Instead of inflicting additional damage with the critical hit, the clockwork Belimarius instead attempts a counteract check with a +18 bonus against one magical effect active on the target."

  - name: "Energize Clockwork Wand"
    desc: "`pf2:1` (concentrate) **Frequency** once per 10 minutes.\n* * *\n\n**Effect** The clockwork mage regains a spell it has already cast that day. It must spend 1 hour of its operational time, or 2 hours if the spell is 3rd rank or higher."
 
```

```encounter-table
name: Clockwork Belimarius
creatures:
  - 1: Clockwork Belimarius
```


Variant clockwork mage

A clockwork mage is a lethal blend of magic and machinery. Each of these clockworks is imbued with an arcane stone at its core that powers spells through the wand embedded in its chest.

* * *

Intricate, complex machines, clockworks are built with care by highly skilled engineers. Though their creation involves some amount of magic, they're primarily mechanical, packed with precision-tuned gears and springs working in concert.

The sturdy mainspring within a clockwork must be wound to provide the energy needed to power the device. Some larger clockworks contain a series of springs for different limbs that each need to be wound. A clockwork's crafter creates a unique metal key while building the clockwork; winding the clockwork usually involves inserting the key into the machine's back and turning clockwise. Larger clockworks require greater strength to turn the key, and typically have larger keys to allow for more torque-some even accommodating a team of winders rather than an individual. Programming a clockwork requires both the key and the knowledge to set the program correctly, information usually reserved for the clockwork's creator or owner.
