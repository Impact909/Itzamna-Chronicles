---
title: "Graytusk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hkU6ZtgoALjjnXU3" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Graytusk"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Graytusk"
level: "Creature 3"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +8, Nature: +7, Survival: +7"
abilityMods: [3, 4, 3, 1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +11, __Will__ +7"
hp: 47
health:
  - name: ""
  - name: HP
    desc: "47"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Studded Leather Armor|+1 Studded Leather Armor]], 40x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+11 (agile, finesse, versatile s)\n__Damage__  1d6 + 5 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+11 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 3 piercing"

  - name: "Double Shot"
    desc: "`pf2:2`  Graytusk can make two ranged Strikes against two different targets, each at a -2 penalty, Graytusk's multiple attack penalty increases only after both attacks are made."
 
```

```encounter-table
name: Graytusk
creatures:
  - 1: Graytusk
```




