---
title: "Quarry Construct"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xt3Yp8NJjHRNmVpl" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/earth
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Quarry Construct"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #187: The Seventh Arch"
name: "Quarry Construct"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[earth]]
trait_03: [[mindless]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9"
abilityMods: [4, -2, 5, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #187: The Seventh Arch_"
ac: 18
armorclass:
  - name: AC
    desc: "18 (14 when broken), construct armor; __Fort__ +11, __Ref__ +4, __Will__ +4"
hp: 23
health:
  - name: ""
  - name: HP
    desc: "23; __Hardness__ 4; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|Warhammer]]"
abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 4)"
    desc: "  Like normal objects, a quarry construct has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once a quarry construct is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 14."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+10 (shove)\n__Damage__  1d8 + 4 bludgeoning"
 
```

```encounter-table
name: Quarry Construct
creatures:
  - 1: Quarry Construct
```




