---
title: "Abysium Horror"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VnfHdAPzYscYvpKu" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Abysium Horror"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Abysium Horror"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Survival: +19"
abilityMods: [7, 3, 5, 3, 3, 3]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +19, __Will__ +17"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ electricity 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Green Glow"
    desc: " (aura,poison,radiation) 20 feet.\n\nAn abysium horror constantly emanates a powerful energy toxic to life. This radiation sheds dim light in the area. Any creature beginning its turn in the aura must attempt a DC 27 Fortitude check save, becoming [[Conditions/Sickened|Sickened 1]] on a failure or [[Conditions/Sickened|Sickened 2]] on a critical failure. Once out of the aura, an affected creature's sickened condition automatically decreases by 1 at the beginning of each of its turns."

  - name: "Heavy"
    desc: "  As long as it is immobile, the elemental can't be forcibly moved or knocked [[Conditions/Prone|Prone]]. If it takes a move action, it loses this immunity until the start of its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (reach 15 feet)\n__Damage__  2d4 poison 2d8 + 10 slashing"

  - name: "**Ranged** `pf2:1` Radioactive Shrapnel"
    desc: "+23 (brutal, propulsive, range increment 60 feet)\n__Damage__  2d4 poison 2d8 + 7 piercing"

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, claw, DC 27 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Abysium Horror
creatures:
  - 1: Abysium Horror
```



A monstrous spider-like creature composed of the radioactive skymetal abysium, this deadly predator contaminates anything it touches.
