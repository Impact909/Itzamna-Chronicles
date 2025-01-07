---
title: "Orc Commander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RU4w76Ov6ryO7dmD" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Orc Commander"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Troubles in Otari"
name: "Orc Commander"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +6, Survival: +5"
abilityMods: [4, 2, 1, -1, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Troubles in Otari_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +6, __Will__ +7"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Maul|Maul]], 6x [[Equipment/Javelin|Javelin]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+10 (shove)\n__Damage__  1d12 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+10 (agile, nonlethal)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+8 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "Battle Cry"
    desc: "`pf2:1` (concentrate,emotion,mental) Bellowing mightily, the commander gives themself and all orc allies within 60 feet who can hear them a +1 status bonus to attack and damage rolls until the start of the orc commander's next turn.\n\n[[Bestiary Effects/Effect_ Battle Cry|Effect: Battle Cry]]"
 
```

```encounter-table
name: Orc Commander
creatures:
  - 1: Orc Commander
```




