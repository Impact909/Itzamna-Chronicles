---
title: "Goliath Spider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DtF2MnjJ39yDsOu6" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Goliath Spider"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Goliath Spider"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +23, Stealth: +22"
abilityMods: [8, 5, 7, -5, 3, -4]
speed: 45 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +25, __Ref__ +21, __Will__ +17"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220"
abilities_top:
  - name: ""

  - name: "Web Sense"
    desc: "  The goliath spider has imprecise tremorsense to detect the vibrations of creatures touching its web.\n* * *\n\nTremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Spring Upon Prey"
    desc: "`pf2:r` (attack) **Requirements** Initiative has not yet been rolled.\n\n**Trigger** A creature touches the goliath spider's web while the spider is on it.\n* * *\n\n**Effect** The goliath spider automatically notices the creature and Strides, Climbs, or Descends on a Web before it rolls initiative."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+24 (reach 10 feet)\n__Damage__  2d12 + 12 piercing plus goliath-spider-venom"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+22 (range increment 60 feet)\n__Damage__ "

  - name: "Descend on a Web"
    desc: "`pf2:1` (move) The goliath spider moves straight down up to 120 feet, suspended by a web line. It can hang from the web or drop off. The distance it Descends on a Web doesn't count for falling damage.\n\nA creature that successfully Strikes the web (AC 20, Hardness 5, 20 HP) severs it, causing the spider to fall."

  - name: "Goliath Spider Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 30 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 2** 3d8 poison damage and [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 3** 3d10 poison damage and [[Conditions/Paralyzed|Paralyzed]] for 2d4 hours"

  - name: "Web Tether"
    desc: "  A creature hit by the spider's web Strike is [[Conditions/Restrained|Restrained]] and tethered to the spider, preventing it from moving farther away from the spider.\n\nThe spider can have one creature tethered at a time. The DC to [[Actions/Escape|Escape]] or [[Actions/Force Open|Force Open]] the web is 30. The tether can be severed with a Strike (AC 20, Hardness 5, HP 20), but this doesn't free the restrained creature."
 
```

```encounter-table
name: Goliath Spider
creatures:
  - 1: Goliath Spider
```



Goliath spiders dwell in the deepest jungles, where they build webs as big as temples and feast on prey as large as hippopotami.

* * *

Few everyday vermin inspire as much dread as the infamous spider.
