---
title: "Bosun"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ddfwT7eEIIsRU6zL" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Bosun"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Bosun"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +9, Intimidation: +9, Sailing Lore: +11"
abilityMods: [2, 4, 1, 0, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +11, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Spear|Naval Pike]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile, nonlethal)\n__Damage__  1d6 + 5 bludgeoning"

  - name: "**Melee** `pf2:1` Naval Pike"
    desc: "+11 ()\n__Damage__  1d6 + 5 piercing"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+13 (agile, versatile s)\n__Damage__  1d4 + 5 piercing"

  - name: "**Ranged** `pf2:1` Naval Pike"
    desc: "+13 (thrown 20 ft.)\n__Damage__  1d6 + 5 piercing"

  - name: "Bosun's Command"
    desc: "`pf2:1` (auditory,concentrate,emotion,linguistic,mental) **Frequency** once per round\n* * *\n\n**Effect** The bosun orders an ally to attack or to get in position. Until the end of the ally's next turn, they gain the bosun's choice of a +2 status bonus to attack rolls or a +10-foot status bonus to their Speeds.\n\n[[Bestiary Effects/Effect_ Bosun's Command|Effect: Bosun's Command]]"

  - name: "Pike and Strike"
    desc: "`pf2:2`  The bosun Strikes with their naval pike.\n\nIf this Strike hits, the bosun can either move the target 5 feet within the pike's reach or make a fist Strike against the target without increasing their multiple attack penalty until after the fist Strike."
 
```

```encounter-table
name: Bosun
creatures:
  - 1: Bosun
```



A ship's boatswain, or bosun, leads the deckhands who maintain the ship.

* * *

Adventurers may need passage on a swift vessel, or they might face danger from raiders at sea or in coastal settlements.
