---
title: "Ferrous Butterfly"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.j9aAUm26thSypCjM" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Ferrous Butterfly"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Ferrous Butterfly"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9"
abilityMods: [2, 4, 3, -4, 0, 0]
speed: 5 feet,  fly 40 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +6, __Ref__ +9, __Will__ +5"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ electricity 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wing"
    desc: "+9 (finesse)\n__Damage__  1 bleed plus a-thousand-cuts 1d4 + 2 slashing plus a-thousand-cuts"

  - name: "A Thousand Cuts"
    desc: "  A ferrous butterfly's knifelike wings cause terrible lacerations that continue to bleed. Any creature with persistent bleed damage from a ferrous butterfly's wing attack has weakness 2 to slashing damage until the bleeding is stopped."

  - name: "Swoop"
    desc: "`pf2:2`  The ferrous butterfly Flies up to its Speed and makes a wing Strike at any point during that movement."
 
```

```encounter-table
name: Ferrous Butterfly
creatures:
  - 1: Ferrous Butterfly
```




