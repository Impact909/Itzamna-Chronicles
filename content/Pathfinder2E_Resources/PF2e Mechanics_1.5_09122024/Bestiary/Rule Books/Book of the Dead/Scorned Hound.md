---
title: "Scorned Hound"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hX78fUGcJzAHelHJ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Scorned Hound"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Scorned Hound"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +7, Stealth: +5, Survival: +5"
abilityMods: [4, 2, 2, -4, 2, -1]
speed: 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +9, __Ref__ +7, __Will__ +5"
hp: 22
health:
  - name: ""
  - name: HP
    desc: "22, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Sense Companion"
    desc: " (detection,occult) A scorned hound knows the direction of its past owner or family (as long as they're both on the same plane), but not the distance."

  - name: "Stench"
    desc: " (aura,olfactory) 15 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 14 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as it's sickened on a critical failure). While within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d6 + 2 piercing"

  - name: "Betray the Pack"
    desc: "  The hound's Strikes deal 1d4 additional damage to creatures that were once its owner, companion, fellow pet, family, household, or pack."
 
```

```encounter-table
name: Scorned Hound
creatures:
  - 1: Scorned Hound
```



Scorned hounds rise from the most devoted dogs. They're incredibly possessive of their owners, allowing no living beings to approach and refusing to be parted.

* * *

Bonds of loyalty that endure beyond death reanimate pets to crawl from their graves within days of dying, returning to the side of their past owners, family, or pack. Unfortunately, death irrevocably changes a risen pet. They return as aggressive, predatory beasts, difficult to control and easy to anger. Even the most friendly and docile of pets becomes sadistic and violent in undeath—fixating first on those it views as competition for the attention of its owners. When a risen pet is jilted, rebuffed, or offended by its owner, it turns on them.
