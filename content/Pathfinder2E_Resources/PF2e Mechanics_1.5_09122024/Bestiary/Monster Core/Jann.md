---
title: "Jann"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iOYAFFwlFb8sRKSR" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2e/creature/type/genie
  - pf2e/creature/type/metal
  - pf2e/creature/type/water
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Jann"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Jann"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[earth]]
trait_03: [[elemental]]
trait_04: [[fire]]
trait_05: [[genie]]
trait_06: [[metal]]
trait_07: [[water]]
trait_08: [[wood]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Muan, Petran, Pyric, Sussuran, Talican, Thalassic; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Arcana: +10, Crafting: +8, Deception: +7, Survival: +11"
abilityMods: [4, 2, 2, 3, 3, 1]
speed: 25 feet,  fly 15 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +10, __Ref__ +10, __Will__ +13"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Resistances__ fire 5, electricity 5, cold 5, air 5, earth 5, metal 5, wood 5, water 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|Composite Shortbow]], [[Equipment/Scimitar|Scimitar]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Commanding Presence"
    desc: " (aura,emotion,fear,mental) 20 feet.\n\nA creature that enters the aura must succeed at a DC 19 Will check save or be [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure) and is then temporarily immune for 1 minute.\n\nA genie (with the exception of another jann) takes a –4 circumstance penalty to its save."

  - name: "Elemental Resistance"
    desc: "  The jann's elemental resistance applies to cold, electricity, and fire damage, as well as all damage from elemental sources (including environmental damage from the elemental planes and damage from anything with the air, earth, fire, metal, water, or wood trait)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+14 (forceful, sweep)\n__Damage__  1d6 + 7 slashing plus all-made-one"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (agile, magical, nonlethal)\n__Damage__  1d4 + 7 bludgeoning plus all-made-one"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+12 (deadly d10, propulsive, range increment 60 feet, reload 0)\n__Damage__  1d6 + 5 piercing plus all-made-one"

  - name: "Arcane Innate Spells"
    desc: "DC 21, attack +13; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (to Astral Plane, Elemental Planes, or the Universe only)]]_; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Invisibility|Invisibility (x2)]]_\n__Cantrips__  __(2nd)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Know the Way|Know the Way]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "All Made One"
    desc: "`pf2:1`  The jann calls upon all of the elements that make up their being to gain an additional arcane spell they can cast at will and empower their Strikes with the element, dealing an extra 1d4 damage of the listed type. These benefits last until the jann uses this ability again.\n\n*   Air [[Spells/Tailwind|Tailwind]], 1d4 electricity;\n*   Earth [[Spells/Pummeling Rubble|Pummeling Rubble]], 1d4 bludgeoning;\n*   Fire [[Spells/Breathe Fire|Breathe Fire]], 1d4 fire;\n*   Metal [[Spells/Thunderstrike|Thunderstrike]], 1d4 electricity;\n*   Water [[Spells/Hydraulic Push|Hydraulic Push]], 1d4 bludgeoning;\n*   Wood [[Spells/Summon Plant or Fungus|Summon Plant or Fungus]], 1d4 piercing."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The jann transforms into any Small or Medium animal. This doesn't affect their statistics, but it could change the damage type of their Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Wanderer's Wish"
    desc: "`pf2:3`  **Frequency** three times per year\n* * *\n\n**Effect** The jann instantly grants the benefits of a critical success with the [[Spells/Wish|Wish]] ritual to a mortal creature. This has no cost. That creature specifies what they wish for, but the interpretation is up to the jann. A jann typically attempts to grant wishes in a way that encourages growth and exploration.\n\nA summoned jann can't use this ability."
 
```

```encounter-table
name: Jann
creatures:
  - 1: Jann
```



All six elements build each jann and fill them with a constant desire to travel, typically jaunting about the Universe. The eldest among geniekind, they command respect from their distant offspring. Any jann can grant wishes, not just shuyookhs—a vestige of their ancient power.

* * *

Before mortal history, genies were some of the first creations of the cosmos to possess free will. Formed of elemental matter, they traversed the Universe and the six elemental planes of air, earth, fire, metal, water, and wood. The genies who remained on each elemental plane found their matter replaced with those elements. Genies of metal and wood appear in _Pathfinder Rage of Elements_.

## Genie Shuyookhs

Older, wiser, and more powerful genies possess greater power and are revered with the title of shuyookh (typically adjusted to "sheikha" if the genie is female or "sheikh" for a male). Generally at least 5 levels higher than a typical example of their kind, a shuyookh gains additional spells. The basics of shuyookhs appear here in sidebars and are detailed further in _Rage of Elements_.

The most wondrous of their powers is their ability to grant wishes three times per year. This is not an innate ability but a ritual practice passed down over time in an attempt to replicate the wish-granting abilities of janns.
