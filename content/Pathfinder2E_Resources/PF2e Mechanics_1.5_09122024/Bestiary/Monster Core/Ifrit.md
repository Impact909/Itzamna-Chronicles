---
title: "Ifrit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GGINNbPsFirxH76I" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2e/creature/type/genie
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Ifrit"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ifrit"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[fire]]
trait_03: [[genie]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Pyric; Truespeech"
skills:
  - name: "Skills"
    desc: "Arcana: +14, Athletics: +22, Crafting: +14, Deception: +19, Diplomacy: +17, Intimidation: +19, Society: +14"
abilityMods: [5, 3, 4, 1, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +17, __Will__ +20"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Immunities__  fire; __Weaknesses__ cold 10, water 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|+1 Striking Scimitar]], [[Equipment/Breastplate|Breastplate]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+21 (fire, forceful, magical, reach 10 feet, sweep)\n__Damage__  2d6 + 11 slashing 2d6 fire"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, magical, reach 10 feet)\n__Damage__  1d4 + 11 bludgeoning 2d6 fire"

  - name: "Arcane Innate Spells"
    desc: "DC 29, attack +19; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (to Astral Plane, Elemental Planes, or the Universe only)]]_; __4th __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Invisibility|Invisibility (x2)]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Ignition|Ignition]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Burning Grasp"
    desc: " (fire) When the ifrit [[Conditions/Grabbed|Grabs]] or [[Conditions/Restrained|Restrains]] a creature, that creature takes 2d6 fire damage, and takes 2d6 fire damage at the end of each of its turns until freed."

  - name: "Combat Grab"
    desc: "`pf2:1`  **Requirements** The ifrit has a hand free\n* * *\n\n**Effect** The ifrit makes a melee Strike. If the Strike hits, the target is [[Conditions/Grabbed|Grabbed]] in the ifrit's free hand."

  - name: "Wings of Flame"
    desc: "`pf2:1` (arcane,fire) The ifrit grows flaming wings from their back. They gain a fly Speed of 35 feet for 1 minute. The flames also create an aura in a 5-foot emanation around the ifrit.\n\nAny creature that ends its turn in the aura takes 2d6 fire damage with a DC 25 Reflex check save."
 
```

```encounter-table
name: Ifrit
creatures:
  - 1: Ifrit
```



The fierce and unforgiving ifrits hail from the Plane of Fire, where they build metropolises and trade centers that draw extraplanar travelers. Many ifrits are tyrannical or warmongering, and most use their might to accomplish their goals.

* * *

Before mortal history, genies were some of the first creations of the cosmos to possess free will. Formed of elemental matter, they traversed the Universe and the six elemental planes of air, earth, fire, metal, water, and wood. The genies who remained on each elemental plane found their matter replaced with those elements. Genies of metal and wood appear in _Pathfinder Rage of Elements_.

## Genie Shuyookhs

Older, wiser, and more powerful genies possess greater power and are revered with the title of shuyookh (typically adjusted to "sheikha" if the genie is female or "sheikh" for a male). Generally at least 5 levels higher than a typical example of their kind, a shuyookh gains additional spells. The basics of shuyookhs appear here in sidebars and are detailed further in _Rage of Elements_.

The most wondrous of their powers is their ability to grant wishes three times per year. This is not an innate ability but a ritual practice passed down over time in an attempt to replicate the wish-granting abilities of janns.
