---
title: "Jaathoom"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CIBSUl4FmoSetR1o" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2e/creature/type/genie
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Jaathoom"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Jaathoom"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[elemental]]
trait_03: [[genie]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Sussuran; (Can&#x27;t Speak Any Language); Cloud of Visions"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Arcana: +11, Athletics: +11, Crafting: +9, Deception: +11, Diplomacy: +13, Society: +9, Stealth: +12"
abilityMods: [4, 5, 2, 2, 2, 4]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +9, __Ref__ +14, __Will__ +11"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|Scimitar]]"
  - name: "Cloud of Visions"
    desc: " (arcane,aura,mental) 60 feet.\n\nA jaathoom has [[Bestiary Ability Glossary/Telepathy|Telepathy]] 60 feet but can only show images, not speak."

abilities_mid:
  - name: ""
  - name: "Naturally Invisible"
    desc: "  The jaathoom is [[Conditions/Invisible|Invisible]] at all times, though when they take a hostile action of any kind, they are [[Conditions/Hidden|Hidden]] instead of undetected until the start of their next turn, as the vague outline of their form is faintly visible for a short period of time."

  - name: "Turbulent Skies"
    desc: " (air,arcane,aura) 20 feet.\n\nAll squares in the emanation are difficult terrain for Striding and Flying creatures. Creatures with the air trait are immune.\n\nThe jaathoom can activate or deactivate this aura as a single action with the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+15 (forceful, reach 10 feet, sweep)\n__Damage__  1d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+16 (agile, finesse, magical, nonlethal, reach 10 feet)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Crashing Wind"
    desc: "+16 (air, arcane, range increment 20 feet)\n__Damage__  1d8 + 8 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 21, attack +13; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (to Astral Plane, Elemental Planes, or the Universe only)]]_; __4th __  _[[Spells/Nightmare|Nightmare]]_, _[[Spells/Vapor Form|Vapor Form]]_; __3rd __  _[[Spells/Ill Omen|Ill Omen]]_, _[[Spells/Illusory Creature|Illusory Creature]]_, _[[Spells/Illusory Object|Illusory Object]]_, _[[Spells/Sleep|Sleep]]_\n__Cantrips__  __(3rd)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The jaathoom transforms into a Small or Medium air elemental or aerial animal, such as an owl. This doesn't affect their statistics, but it could change the damage type of their Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Hurricane Blast"
    desc: "`pf2:1` (air,arcane) **Frequency** once per round\n* * *\n\n**Effect** The jaathoom moves all creatures without the air trait in their turbulent skies aura 20 feet directly away, clockwise, or counterclockwise. A creature avoids being moved if it succeeds at a DC 21 Fortitude check save."

  - name: "Ominous Dreams"
    desc: "`pf2:2` (mental,prediction) The jaathoom sends a prophetic dream to a sleeping creature within 10 feet. An unwilling creature avoids the vision if it succeeds at a DC 23 Will check save.\n\nThe jaathoom chooses the dream's subject, but not its exact events. The target sees a brief vision of its future related to that subject, with the effect of [[Spells/Augury|Augury]]. If the result is bad or mixed, the creature is [[Conditions/Frightened|Frightened 2]] and can't recover from being frightened until it wakes."
 
```

```encounter-table
name: Jaathoom
creatures:
  - 1: Jaathoom
```



Possessing all the subtlety and elegance of air itself, the jaathooms of the Plane of Air operate within dreams, nightmares, and time.

* * *

Before mortal history, genies were some of the first creations of the cosmos to possess free will. Formed of elemental matter, they traversed the Universe and the six elemental planes of air, earth, fire, metal, water, and wood. The genies who remained on each elemental plane found their matter replaced with those elements. Genies of metal and wood appear in _Pathfinder Rage of Elements_.

## Genie Shuyookhs

Older, wiser, and more powerful genies possess greater power and are revered with the title of shuyookh (typically adjusted to "sheikha" if the genie is female or "sheikh" for a male). Generally at least 5 levels higher than a typical example of their kind, a shuyookh gains additional spells. The basics of shuyookhs appear here in sidebars and are detailed further in _Rage of Elements_.

The most wondrous of their powers is their ability to grant wishes three times per year. This is not an innate ability but a ritual practice passed down over time in an attempt to replicate the wish-granting abilities of janns.
