---
title: "Living Whirlwind"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.b97yZ74EaUY0pLgC" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Living Whirlwind"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Living Whirlwind"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Stealth: +14"
abilityMods: [3, 5, 2, -2, 1, 0]
speed:  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +9, __Ref__ +16, __Will__ +10"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Disperse"
    desc: "`pf2:r` (air) **Trigger** The living whirlwind takes damage from a hostile action;\n* * *\n\n**Effect** The living whirlwind disperses. Until the end of the current turn, it can't be attacked or targeted, doesn't take up space, and its high winds aura is suppressed.\n\nAt the end of the turn, the living whirlwind reforms in any unoccupied space within 25 feet of where it dispersed, and its high winds are restored."

  - name: "High Winds"
    desc: " (air,aura) 20 feet.\n\nAir within the emanation is difficult terrain for Flying creatures that don't have the air trait."

  - name: "Swiftness"
    desc: "  The living whirlwind's movement doesn't trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+14 (finesse, reach 10 feet)\n__Damage__  2d6 + 7 bludgeoning"

  - name: "Forceful Winds"
    desc: "`pf2:2` (air) The living whirlwind creates a 60-foot line of violent wind. Creatures in the area must succeed at a DC 25 Fortitude check save or be pushed back 10 feet and knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Living Whirlwind
creatures:
  - 1: Living Whirlwind
```



A living whirlwind resembles a dust devil with a vague mouth and eyes formed among the dust and debris swirling within it.

* * *

Hailing from the Plane of Air, these beings appear in a variety of sizes and shapes. They're noted for being elusive, swift, and often difficult to detect due to being composed primarily of air.
