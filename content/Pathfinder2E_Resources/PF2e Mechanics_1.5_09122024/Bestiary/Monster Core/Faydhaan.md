---
title: "Faydhaan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cd3SDQnbMbz4E1fU" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/genie
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Faydhaan"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Faydhaan"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[genie]]
trait_03: [[water]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Wavesense (Imprecise) 60 Feet"
languages: "Common, Thalassic, Muan, Petran, Pyric, Sussuran, Talican; Truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Crafting: +16, Deception: +18, Diplomacy: +20, Nature: +18, Performance: +20, Society: +16, Stealth: +18"
abilityMods: [4, 5, 2, 1, 3, 5]
speed: 25 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +17, __Ref__ +18, __Will__ +18"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Resistances__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|+1 Striking Trident]]"
  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Turbulent Seas"
    desc: " (aura,water) 40 feet.\n\nWater in the aura that is also in the same body of water as the faydhaan is difficult terrain for Swimming creatures. Creatures with the water trait are immune."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Trident"
    desc: "+20 (magical, reach 10 feet)\n__Damage__  2d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, magical, nonlethal, reach 10 feet)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+21 (magical, thrown 20 ft.)\n__Damage__  2d8 + 10 piercing"

  - name: "Arcane Innate Spells"
    desc: "DC 24, attack +12; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (to Astral Plane, Elemental Planes, or the Universe only)]]_; __5th __  _[[Spells/Control Water|Control Water (At Will)]]_, _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Truespeech|Truespeech (At Will)]]_; __4th __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_; __2nd __  _[[Spells/Create Water|Create Water (At Will)]]_, _[[Spells/Invisibility|Invisibility (x2)]]_, _[[Spells/Water Breathing|Water Breathing]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The faydhaan transforms into a Small or Medium water elemental, aquatic animal, or humanoid. This doesn't affect their statistics, but it could change the damage type of their Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Gift of Hospitality"
    desc: "`pf2:3` (arcane,emotion,mental) The faydhaan gives another willing creature a magical gift or an agreeable conversation. The creature gains a +2 status bonus to Society and Diplomacy checks. A creature can't have more than one gift at a time, and a faydhaan can't grant more than one gift at a time.\n\nThe gift ends if the target acts hostile, or if the faydhaan renounces the recipient (a single action).\n\n[[Bestiary Effects/Effect_ Gift of Hospitality|Effect: Gift of Hospitality]]"

  - name: "Skewer"
    desc: "`pf2:1`  The faydhaan makes a trident Strike, dealing an extra 2d6 persistent bleed damage on a hit (4d6 on a critical hit)."
 
```

```encounter-table
name: Faydhaan
creatures:
  - 1: Faydhaan
```



The faydhaans of the Plane of Water are more powerful than the other genies dwelling on the elemental planes, but they prefer to forge alliances through diplomacy and flattery.

* * *

Before mortal history, genies were some of the first creations of the cosmos to possess free will. Formed of elemental matter, they traversed the Universe and the six elemental planes of air, earth, fire, metal, water, and wood. The genies who remained on each elemental plane found their matter replaced with those elements. Genies of metal and wood appear in _Pathfinder Rage of Elements_.

## Genie Shuyookhs

Older, wiser, and more powerful genies possess greater power and are revered with the title of shuyookh (typically adjusted to "sheikha" if the genie is female or "sheikh" for a male). Generally at least 5 levels higher than a typical example of their kind, a shuyookh gains additional spells. The basics of shuyookhs appear here in sidebars and are detailed further in _Rage of Elements_.

The most wondrous of their powers is their ability to grant wishes three times per year. This is not an innate ability but a ritual practice passed down over time in an attempt to replicate the wish-granting abilities of janns.
