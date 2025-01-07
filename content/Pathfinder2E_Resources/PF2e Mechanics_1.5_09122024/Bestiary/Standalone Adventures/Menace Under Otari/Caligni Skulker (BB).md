---
title: "Caligni Skulker (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.x1co4E1k4aXlA3d9" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Caligni Skulker (BB)"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Caligni Skulker (BB)"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[caligni]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +4, Stealth: +10, Thievery: +8"
abilityMods: [0, 4, 3, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +9, __Ref__ +10, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]]"
  - name: "[[Menace Under Otari/Caligni Dancer (BB)/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the caligni can't see until the end of their next turn. All squares are difficult terrain for them, and they take a -4 status penalty to Perception. If they try to attack a creature, the attack fails unless they succeed at a DC 11 Flat check. Light doesn't blind them again for 1 hour."

abilities_mid:
  - name: ""
  - name: "Final Night"
    desc: "  When a caligni skulker dies, their body dissolves fog of inky darkness. All light sources within 20 feet are extinguished. Any light spells in the area go out for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+10 (agile, finesse, versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+10 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "[[Menace Under Otari/Caligni Hunter (BB)/Darkening Poison|Darkening Poison]]"
    desc: "`pf2:1` (poison) The next time the skulker deals damage with a dagger Strike, the target must succeed at a DC 16 Fortitude check save or take 1d8 poison damage and treat all creatures as [[Conditions/Concealed|Concealed]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Darkvision|Sneak Attack]]"
    desc: "  The caligni skulker deals an extra 1d6 damage to creatures that have the [[Conditions/Off-Guard|Off-Guard]] condition."
 
```

```encounter-table
name: Caligni Skulker (BB)
creatures:
  - 1: Caligni Skulker (BB)
```



Caligni lurk in subterranean cities, and they relish the chance to creep above ground at night to steal resources, spy on surface dwellers, or simply cause mischief.
