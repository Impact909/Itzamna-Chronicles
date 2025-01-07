---
title: "Dwarf Stonecaster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.195XA8N33Faz4qpH" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Dwarf Stonecaster"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dwarf Stonecaster"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[humanoid]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Tremorsense (Imprecise) 10 Feet"
languages: "Common, Dwarven, Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Crafting: +8, Nature: +12, Dwarven Lore: +8"
abilityMods: [4, 2, 3, 2, 5, -1]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +8, __Will__ +14"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|Staff]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 10 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+12 (two-hand d8)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Clan Dagger"
    desc: "+12 (agile, parry, versatile b)\n__Damage__  1d4 + 4 piercing"

  - name: "Boulder Roll"
    desc: "`pf2:2` (earth,primal) The stonecaster conjures a rolling boulder that deals 5d6 bludgeoning damage to each creature in a 60-foot line with a DC 21 Reflex check save.\n\nThe stonecaster can't use Boulder Roll again for 1d4 rounds."

  - name: "Dwarven Doughtiness"
    desc: "  A dwarf is often calm and collected in the face of imminent danger. At the end of this dwarf's turn, reduce their frightened condition by 2 instead of 1."

  - name: "Tremor"
    desc: "`pf2:1` (earth,primal) The stonecaster causes the earth below to tremble. Each creature on the ground in a 10-foot emanation takes 2d8 bludgeoning damage with a DC 21 Fortitude check save. A creature that critically fails is knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Dwarf Stonecaster
creatures:
  - 1: Dwarf Stonecaster
```



All dwarves share a connection to the earth, but stonecasters have focused and polished that connection. Their years of meditation have granted them the ability to create boulders and shake the very earth. These elemental specialists are often highly respected in their community, which prizes their art of geomancy. Young dwarves who show a stronger than normal connection to the earth might be sent to a stonecaster to train at an early age.

* * *

A dwarf's strength comes from their stoic determination, quality equipment, and their ability to hold grudges for centuries.
