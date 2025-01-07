---
title: "Hunting Spider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GKw9xfwzlv458IVe" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Hunting Spider"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hunting Spider"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +5, Stealth: +7"
abilityMods: [2, 4, 1, -5, 2, -4]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +6, __Ref__ +9, __Will__ +5"
hp: 16
health:
  - name: ""
  - name: HP
    desc: "16"
abilities_top:
  - name: ""

  - name: "Web Sense"
    desc: "  The hunting spider has imprecise tremorsense to detect the vibrations of creatures touching its web.\n* * *\n\nTremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Spring Upon Prey"
    desc: "`pf2:r` (attack) **Requirements** Initiative has not yet been rolled.\n\n**Trigger** A creature touches the hunting spider's web while the spider is on it.\n* * *\n\n**Effect** The hunting spider automatically notices the creature and Strides, Climbs, or Descends on a Web before it rolls initiative."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+9 (finesse)\n__Damage__  1d6 + 2 piercing plus hunting-spider-venom"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+7 (range increment 30 feet)\n__Damage__ "

  - name: "Descend on a Web"
    desc: "`pf2:1` (move) The hunting spider moves straight down up to 40 feet, suspended by a web line. It can hang from the web or drop off. The distance it Descends on a Web doesn't count for falling damage.\n\nA creature that successfully Strikes the web (AC 20, Hardness 3, 5 HP) severs it, causing the spider to fall."

  - name: "Hunting Spider Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and off-guard (1 round)\n\n**Stage 3** 1d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and off-guard (1 round)"

  - name: "Web Trap"
    desc: "  A creature hit by the hunting spider's web Strike is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface until it [[/act escape dc=17]]{Escapes (DC 17)}."
 
```

```encounter-table
name: Hunting Spider
creatures:
  - 1: Hunting Spider
```



Hunting spiders are the most common type of giant spider, though not the largest.

* * *

Few everyday vermin inspire as much dread as the infamous spider.
