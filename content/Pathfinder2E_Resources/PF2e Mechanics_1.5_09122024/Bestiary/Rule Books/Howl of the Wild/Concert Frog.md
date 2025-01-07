---
title: "Concert Frog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.09SoHwWf3HMMAn9R" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Concert Frog"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Concert Frog"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +16, Performance: +19, Stealth: +12"
abilityMods: [5, 3, 6, -4, 2, 4]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +13, __Will__ +16"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, 25 (froglets, immune to area damage))"
abilities_top:
  - name: ""

  - name: "Conduct"
    desc: "`pf2:1` (auditory,mental,primal) One of the froglets begins to sing, granting one of three effects to the concert frog and all allies within 60 feet until the beginning of the concert frog's next turn.\n\n[[Bestiary Effects/Effect_ Conduct|Effect: Conduct]]\n\n*   **Red** Grants a +10-foot status bonus to their Speeds.\n*   **Blue** Grants a +1 status bonus to AC and Fortitude saving throws.\n*   **Yellow** Allies gain a +1 status bonus to attack rolls and deal an additional 1d4 sonic damage on successful melee Strikes as their attacks resonate."

  - name: "Three-Frog Orchestra"
    desc: "  The concert frog has three froglets perched behind its lips, each of a different color. A creature can specifically target a froglet. If any froglets have died, the concert frog attempts a DC 11 Flat check at the end of its turn; on a success, new froglets hatch in its stomach and emerge at the concert frog's lips."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 ()\n__Damage__  2d10 + 11 piercing"

  - name: "**Ranged** `pf2:1` Croak"
    desc: "+17 (range 30 feet, sonic)\n__Damage__  2d8 + 9 sonic"
 
```

```encounter-table
name: Concert Frog
creatures:
  - 1: Concert Frog
```



These massive frogs store their eggs inside their stomach. When an egg hatches, the froglet crawls its way up into its parent's mouth to add its celebratory chirps and croaks to the family's song.
