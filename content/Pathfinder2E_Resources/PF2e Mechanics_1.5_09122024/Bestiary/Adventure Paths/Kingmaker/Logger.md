---
title: "Logger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aWRjVZjbXakiXhDf" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Logger"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Logger"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +7, Nature: +4, Survival: +6, Lumber Lore: +6"
abilityMods: [3, 1, 2, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +8, __Ref__ +5, __Will__ +6"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|Battle Axe]], [[Equipment/Hatchet|Hatchet]], [[Equipment/Padded Armor|Padded Armor]], [[Equipment/Climbing Kit|Climbing Kit]]"
abilities_mid:
  - name: ""
  - name: "Tandem Chop"
    desc: "`pf2:r`  **Trigger** A creature or object within their reach is hit with a Strike by an ally using a weapon in the axe group\n\n**Requirements** The logger is holding a weapon in the axe group\n\n**Effect** The logger attempts a Strike against the same creature or object. If it hits, combine the damage with the damage from the triggering Strike for the purpose of Hardness, resistances, and weaknesses. A creature or object can only be the target of a single Tandem Chop per turn, regardless of the number of loggers in reach."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+7 (sweep)\n__Damage__  1d8 + 3 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+7 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 3 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+5 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 1 slashing"
 
```

```encounter-table
name: Logger
creatures:
  - 1: Logger
```




