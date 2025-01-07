---
title: "Navigator"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.z9AmbjwPZ2CnYMHp" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Navigator"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Navigator"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Nature: +11, Society: +8, Survival: +9, Sailing Lore: +14"
abilityMods: [0, 2, 1, 4, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +8, __Will__ +9"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], Scroll Case with Ship's Charts, [[Equipment/Writing Set|Writing Set]]"
  - name: "Chart a Course"
    desc: " (concentrate) By spending 10 minutes of work and succeeding at a Sailing Lore check, the navigator plots an optimal course.\n\nThe severity of environmental conditions other than temperature are reduced by one step for 24 hours (two steps on a critical success). This changes moderate damage to minor damage, winds that create greater difficult terrain cause only difficult terrain, and so on."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+8 (agile, finesse, versatile s)\n__Damage__  1d4 + 4 piercing plus navigators-edge"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+8 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing plus navigators-edge"

  - name: "Navigator's Edge"
    desc: "  The navigator deals an additional 1d6 weapon damage when on a ship."
 
```

```encounter-table
name: Navigator
creatures:
  - 1: Navigator
```



A navigator uses celestial bodies and shipping lanes to determine routes. For noncombat tasks involving navigation or sailing, the navigator is a 4th-level challenge.

* * *

Adventurers may need passage on a swift vessel, or they might face danger from raiders at sea or in coastal settlements.
