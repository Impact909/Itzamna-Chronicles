---
title: "Hexmoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xaeZIg5KOVH0cV0F" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Hexmoth"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Hexmoth"
level: "Creature 8"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Arcana: +18, Stealth: +14"
abilityMods: [3, 6, 3, -4, 1, 2]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +16, __Will__ +11"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105; __Immunities__  acid; __Resistances__ spells 10"
abilities_top:
  - name: ""

  - name: "Arcanosense"
    desc: "  A hexmoth can sense sources of magic at the listed range as though it has a 4th-rank [[Spells/Detect Magic|Detect Magic]] constant innate spell."

abilities_mid:
  - name: ""
  - name: "Advanced Arcanovore"
    desc: "  A hexmoth has resistance 10 against all damage caused by spells. It's immune to one type of energy it consumed most as a hexworm, typically acid, cold, electricity, fire, or sonic."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Proboscis"
    desc: "+13 ()\n__Damage__  2d10 + 9 piercing plus arcane-consumption"

  - name: "**Ranged** `pf2:1` Hexbolt"
    desc: "+13 (range 30 feet)\n__Damage__  2d8 + 6 untyped"

  - name: "Arcane Consumption"
    desc: "`pf2:1`  The hexmoth attempts to consume the magic of an adjacent magical effect or unattended magic item. It attempts a counteract check against the target with a +16 modifier. On a success, the magical effect ends. A magic item instead becomes a mundane item for 1 round. The hexmoth gains 2d8 healing Hit Points."

  - name: "Arcanotaxis"
    desc: "  **Requirements** The hexmoth has detected a source of magic with its arcanosense\n\n**Trigger** The hexmoth's turn begins\n* * *\n\n**Effect** The hexmoth Flies or Strides up to its Speed toward the nearest source of magic it can detect."

  - name: "Hexdust Wind"
    desc: "`pf2:2`  With a few fierce wingbeats, the hexmoth expels magical scale dust in a 30-foot cone. This deals 10d6 untyped damage of the type to which the hexmoth is immune (DC 23 Fortitude check save). It can't use Hexdust Wind again for 1d4 rounds."
 
```

```encounter-table
name: Hexmoth
creatures:
  - 1: Hexmoth
```




