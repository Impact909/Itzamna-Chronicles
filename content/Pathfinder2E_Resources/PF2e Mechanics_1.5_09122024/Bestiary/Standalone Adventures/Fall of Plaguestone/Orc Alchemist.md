---
title: "Orc Alchemist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OO1ifCNfBBIjXf5c" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Orc Alchemist"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Orc Alchemist"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +6, Crafting: +9, Stealth: +7"
abilityMods: [2, 3, 3, 3, 0, -1]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +9, __Ref__ +9, __Will__ +4"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Acid Flask (Lesser)|Acid Flask (Lesser)]], 2x [[Equipment/Alchemist's Fire (Lesser)|Alchemist's Fire (Lesser)]], 2x [[Equipment/Bottled Lightning (Lesser)|Bottled Lightning (Lesser)]], [[Equipment/Orc Knuckle Dagger|Orc Knuckle Dagger]], 2x [[Equipment/Elixir of Life (Minor)|Elixir of Life (Minor)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Knuckle Dagger"
    desc: "+8 (agile, disarm)\n__Damage__  1d6 + 2 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Acid Flask"
    desc: "+9 (range increment 20 feet, splash)\n__Damage__  1 acid 1d6 acid 1 acid"

  - name: "**Ranged** `pf2:1` Alchemist&#x27;s Fire"
    desc: "+9 (range increment 20 feet, splash)\n__Damage__  1d8 fire 1 fire 1 fire"

  - name: "**Ranged** `pf2:1` Bottled Lightning"
    desc: "+9 (range increment 20 feet, splash)\n__Damage__  1d6 electricity 1 electricity"
 
```

```encounter-table
name: Orc Alchemist
creatures:
  - 1: Orc Alchemist
```




