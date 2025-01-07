---
title: "Sprite"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VZ3sfiMH2vCoacT2" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/sprite
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Sprite"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sprite"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[fey]]
trait_02: [[sprite]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Low-Light Vision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Stealth: +6"
abilityMods: [-3, 4, 0, -2, 0, 2]
speed: 10 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +2, __Ref__ +8, __Will__ +4"
hp: 7
health:
  - name: ""
  - name: HP
    desc: "7; __Weaknesses__ cold iron 3"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Rapier|Rapier]]"
  - name: "Luminous Fire"
    desc: " (light,primal) A sprite naturally sheds light like a torch. The sprite can extinguish, rekindle, or change the color of this light by using an action with the concentrate trait. While this light is extinguished, the sprite's Strikes don't deal fire damage, and they can't use their luminous spark Strike."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+8 (deadly d8, disarm, finesse, fire, magical)\n__Damage__  1d6 - 3 piercing"

  - name: "**Ranged** `pf2:1` Luminous Spark"
    desc: "+8 (fire, light, range 20 feet)\n__Damage__  1d4 fire"

  - name: "Primal Innate Spells"
    desc: "DC 16, attack +8; __1st __  _[[Spells/Dizzying Colors|Dizzying Colors]]_\n__Cantrips__  __(1st)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Light|Light]]_"
 
```

```encounter-table
name: Sprite
creatures:
  - 1: Sprite
```



Common sprites, sometimes called firefly sprites, are primeval guardians that latch onto a person, place, or object and defend it for their own inscrutable reasons. Their dispositions vary from kind to spiteful, but all sprites have a capricious streak. Being only about 9 inches tall, they are wary of animals that might hunt them, particularly house cats, and prefer flight to a fight. On the other hand, sprites are incredibly curious about all forms of magic and heedlessly gather around ley line nexuses or other places of power.

* * *

Elusive, flighty, and ebullient, sprites are what many villagers first imagine when they hear the terms "fey" or "fairy." While their dispositions vary, all sprites share a connection to magic and a diminutive size. This family of fey shares its name with its slightest and most populous member, the common sprite.
