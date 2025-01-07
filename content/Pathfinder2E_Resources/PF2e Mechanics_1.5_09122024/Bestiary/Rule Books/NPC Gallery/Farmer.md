---
title: "Farmer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UHMBr1qTOSp84RYE" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Farmer"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Farmer"
level: "Creature 0"

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
    desc: "Athletics: +5, Nature: +4, Survival: +4, Farming Lore: +4"
abilityMods: [3, 1, 3, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +7, __Ref__ +5, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|Pitchfork]], [[Equipment/Leather Armor|Leather Armor]], 4x [[Equipment/Rations|Apple]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pitchfork"
    desc: "+6 (reach 10 feet)\n__Damage__  1d6 + 3 piercing"

  - name: "**Ranged** `pf2:1` Apple"
    desc: "+5 (agile, nonlethal, thrown 20 ft.)\n__Damage__  1d4 + 3 bludgeoning"

  - name: "Pitch Bale"
    desc: "`pf2:1`  **Requirements** The farmer's last action was a successful pitchfork Strike\n* * *\n\n**Effect** The farmer moves the creature they hit with their pitchfork up to 5 feet, and the target falls [[Conditions/Prone|Prone]]. The target can attempt a DC 13 Reflex check save to avoid falling prone, and avoids being moved altogether on a critical success."
 
```

```encounter-table
name: Farmer
creatures:
  - 1: Farmer
```



Workers of the fields, vineyards, and orchards of the world, farmers are known for their rugged endurance and their skill with both plants and animals.

* * *

Every day, laborers perform backbreaking physical work.
