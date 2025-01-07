---
title: "Kobold Trapmaster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HLa0lQwUcOwunWM1" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Kobold Trapmaster"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Troubles in Otari"
name: "Kobold Trapmaster"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[kobold]]
trait_04: [[lawful]]
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
sourcebook: "_Pathfinder Adventure: Troubles in Otari_"
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
    desc: "[[Equipment/Shortsword|Shortsword]], 3x [[Equipment/Spear|Spear]], [[Equipment/Leather Armor|Leather Armor]], 3x [[Equipment/Spike Snare|Spike Trap]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+8 (agile, finesse, versatile s)\n__Damage__  1d6 + 2 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+10 (thrown 20 ft.)\n__Damage__  1d6 + 2 piercing"

  - name: "Hurried Retreat"
    desc: "`pf2:1`  If the kobold is adjacent to at least one enemy, the kobold Strides up to 30 feet and gains a +2 circumstance bonus to AC against reactions triggered by this movement. They must end this movement in a space that's not adjacent to any enemy."

  - name: "Quick Trap"
    desc: "`pf2:3`  The kobold trapmaster deploys one spike trap in an adjacent square."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The kobold trapmaster deals an extra 1d6 damage to creatures that have the [[Conditions/Off-Guard|Off-Guard]] condition."

  - name: "Spike Trap"
    desc: "  Once this trap is deployed, anyone who steps on the square it's in takes 2d8 piercing damage and must attempt a DC 17 Reflex check saving throw."
 
```

```encounter-table
name: Kobold Trapmaster
creatures:
  - 1: Kobold Trapmaster
```



Kobold trapmasters are the masterminds behind crafting and implementing wily traps in kobold lairs, and are widely respected among their kind.
