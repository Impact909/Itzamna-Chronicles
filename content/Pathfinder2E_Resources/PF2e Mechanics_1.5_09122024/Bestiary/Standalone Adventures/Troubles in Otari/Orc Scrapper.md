---
title: "Orc Scrapper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W76BZRDVcMIbcIx4" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Orc Scrapper"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Troubles in Otari"
name: "Orc Scrapper"
level: "Creature 1"

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
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +7, Intimidation: +4, Survival: +4"
abilityMods: [4, 2, 3, -1, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Troubles in Otari_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +7, __Will__ +4"
hp: 23
health:
  - name: ""
  - name: HP
    desc: "23"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x [[Equipment/Javelin|Javelin]], [[Equipment/Battle Axe|Battle Axe]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+7 (sweep)\n__Damage__  1d8 + 4 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal)\n__Damage__  1d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+5 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"
 
```

```encounter-table
name: Orc Scrapper
creatures:
  - 1: Orc Scrapper
```




