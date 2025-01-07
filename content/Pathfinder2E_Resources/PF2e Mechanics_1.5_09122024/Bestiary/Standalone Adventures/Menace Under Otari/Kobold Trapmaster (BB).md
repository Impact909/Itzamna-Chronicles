---
title: "Kobold Trapmaster (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.S6NoqH06lLcVdOwI" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Kobold Trapmaster (BB)"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Kobold Trapmaster (BB)"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[humanoid]]
trait_02: [[kobold]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Crafting: +8, Stealth: +7"
abilityMods: [2, 4, 1, 4, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +10, __Will__ +5"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Shortsword, 3x Spear, Leather Armor, [[Equipment/Spike Snare|Spike Trap]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+8 (agile, finesse, versatile s)\n__Damage__  1d6 + 2 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+10 (thrown 20 ft.)\n__Damage__  1d6 + 2 piercing"

  - name: "Quick Trap"
    desc: "`pf2:3`  The kobold trapmaster deploys one of their spike traps in an adjacent square.\n* * *\n\nOnce this trap is deployed in a square, it deals 2d8 piercing damage to anyone who steps on that square and they must attempt a DC 17 Reflex check saving throw. A hero takes no damage on a critical success, half damage on a success, full damage on a failure, and double damage on a critical failure. These traps can be disabled with a successful DC 15 Thievery check check."

  - name: "[[Menace Under Otari/Kobold Dragon Mage (Green, BB)/Scamper|Scamper]]"
    desc: "`pf2:1`  If the kobold is adjacent to at least one enemy, the kobold Strides up to 30 feet and gains a +2 circumstance bonus to AC against reactions triggered by this movement. The kobold must end this movement in a space that's not adjacent to any enemy."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The kobold trapmaster deals an extra 1d6 damage to creatures that have the [[Conditions/Off-Guard|Off-Guard]] condition."
 
```

```encounter-table
name: Kobold Trapmaster (BB)
creatures:
  - 1: Kobold Trapmaster (BB)
```



Kobold trapmasters are the masterminds behind crafting and implementing wily traps in kobold lairs, and are widely respected among their kind.
