---
title: "Basilisk (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hQruqFGuGjVDvWf3" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Basilisk (BB)"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Basilisk (BB)"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +8"
abilityMods: [4, -1, 5, -3, 2, 1]
speed: 20 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +8, __Will__ +11"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  Petrifying Glance,  Petrifying Gaze"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Petrifying Glance"
    desc: "`pf2:r` (arcane,aura) When a creature the basilisk can see within 30 feet starts its turn, the basilisk can use its reaction to glance at the creature.\n\nThe creature must attempt a DC 20 Fortitude check save. If it fails, it gains the [[Conditions/Slowed|Slowed 1]] condition for 1 minute as its body slowly stiffens."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 ()\n__Damage__  2d8 + 4 piercing"

  - name: "Petrifying Gaze"
    desc: "`pf2:2` (arcane,concentrate) The basilisk stares at a creature it can see within 30 feet. If the creature can see the basilisk, that creature must attempt a DC 22 Fortitude check save.\n\nIf it fails and hasn't already gained the slowed condition from Petrifying Glance or this ability, it gains the [[Conditions/Slowed|Slowed 1]] condition. If the creature fails this save when it already has the slowed condition from this ability or Petrifying Glance, the creature is permanently turned to [[Conditions/Petrified|Stone]].\n\nA creature petrified in this manner that is coated with fresh basilisk blood is instantly restored to flesh. A single basilisk contains enough blood to coat up to 2 creatures in this manner."
 
```

```encounter-table
name: Basilisk (BB)
creatures:
  - 1: Basilisk (BB)
```



A basilisk is an eight-legged reptile that can turn creatures to stone just by looking at them.
