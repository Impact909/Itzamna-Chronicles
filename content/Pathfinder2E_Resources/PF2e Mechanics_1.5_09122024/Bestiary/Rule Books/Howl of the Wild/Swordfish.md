---
title: "Swordfish"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9Dc4IogAYKzYOnPo" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Swordfish"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Swordfish"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +12"
abilityMods: [5, 3, 1, -4, 2, 0]
speed:  swim 60 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +12, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50"
abilities_top:
  - name: ""

  - name: "Warm Brain"
    desc: "  **Requirements** The swordfish is in cold water\n\n**Trigger** The swordfish rolls initiative\n* * *\n\n**Effect** The swordfish [[Actions/Seek|Seeks]] or [[Actions/Swim|Swims]]."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bill"
    desc: "+12 (sweep)\n__Damage__  1d10 + 5 slashing"

  - name: "Fast Sweep"
    desc: "`pf2:1`  **Frequency** once per turn\n* * *\n\n**Effect** The swordfish makes two bill Strikes against two adjacent targets, with a +1 circumstance bonus to its attack rolls."
 
```

```encounter-table
name: Swordfish
creatures:
  - 1: Swordfish
```



Contrary to popular belief, the bill of the swordfish is not used for impaling its prey, but to stun or slash. Specialized organs help keep it warm in the coldest waters, increasing its already considerable speed and reflexes.
