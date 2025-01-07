---
title: "Hexworm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JTeCDqWHMSAk2IYx" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Hexworm"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Hexworm"
level: "Creature 4"

alignment: ""
size: "tiny"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Arcana: +12, Stealth: +9"
abilityMods: [2, 4, 3, -5, 1, 0]
speed: 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +14, __Will__ +6"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Resistances__ spells 5"
abilities_top:
  - name: ""

  - name: "Arcanosense"
    desc: "  A hexworm can sense sources of magic at the listed range as though it has a 4th-rank [[Spells/Detect Magic|Detect Magic]] constant innate spell."

abilities_mid:
  - name: ""
  - name: "Arcanovore"
    desc: "  A hexworm has resistance 5 against all damage caused by spells."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+8 ()\n__Damage__  2d6 + 2 piercing plus arcane-consumption"

  - name: "Arcane Consumption"
    desc: "`pf2:1`  The hexworm attempts to consume the magic of an adjacent magical effect or unattended magic item. It attempts a counteract check against the target with a +11 modifier. On a success, the magical effect ends. A magic item instead becomes a mundane item for 1 round. The hexworm gains 2d8 healing Hit Points."

  - name: "Arcanotaxis"
    desc: "  **Requirements** The hexworm has detected a source of magic with its arcanosense\n\n**Trigger** The hexworm's turn begins\n* * *\n\n**Effect** The hexworm Strides up to its Speed toward the nearest source of magic it can detect."
 
```

```encounter-table
name: Hexworm
creatures:
  - 1: Hexworm
```




