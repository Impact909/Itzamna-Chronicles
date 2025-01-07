---
title: "Dromaar Mountaineer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yk9lyBJF96c06z1K" 
tags:
  - pf2e/creature/type/dromaar
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Dromaar Mountaineer"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dromaar Mountaineer"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[dromaar]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +7, Survival: +8"
abilityMods: [3, 3, 1, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +7, __Ref__ +9, __Will__ +8"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Pick|Pick]], 6x [[Equipment/Bola|Bola]], [[Equipment/Hide Armor|Hide Armor]], [[Equipment/Rope|Rope]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pick"
    desc: "+9 (fatal d10)\n__Damage__  1d6 + 3 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+9 (agile, shove)\n__Damage__  1d6 + 3 bludgeoning"

  - name: "**Ranged** `pf2:1` Bola"
    desc: "+9 (nonlethal, ranged trip, thrown 20 ft.)\n__Damage__  1d6 + 3 bludgeoning"

  - name: "Tangle Prey"
    desc: "`pf2:1`  The dromaar draws a bola and Strikes a target within 20 feet. On a success, the dromaar immediately rolls an Athletics check check against the target's Fortitude DC to [[Actions/Trip|Trip]] them."
 
```

```encounter-table
name: Dromaar Mountaineer
creatures:
  - 1: Dromaar Mountaineer
```



Dromaar mountaineers are hardened half-orc scouts who often lead raiding or scouting parties on dangerous expeditions. Dromaar scouts who lead many successful expeditions can rise to positions of prominence within their holds, and those who command enough loyalty may even claim a hold of their own.

* * *

Many orcs are forged in the fires of violence and conflict, often from the moment they're born. As they live lives that are frequently cut brutally short, orcs revel in testing their strength against worthy foes, whether by challenging a higher-ranking member of their community for dominance, taming a powerful beast, or slaying a fearsome monster.

Tall and powerful, with long arms and thickly muscled legs, many orcs top 7 feet in height. Their heavy limbs and broad, almost bow-legged stances combine with a tendency to slouch forward to create an almost contradictory set of circumstances where an orc can tower over other humanoids while simultaneously staring them in the eye. These features, alongside a tendency to scar easily, can make them seem quite intimidating.

The half-orc dromaars, most commonly born of unions between orcs and humans, are often tested even more harshly than their full orc kin, but those who endure these tests can rise to positions of authority. "An orc can have what an orc can hold" is a saying that not only applies to an individual's ability to secure their own destiny and position, but is also likely the root of orcs referring to their communities as holds.
