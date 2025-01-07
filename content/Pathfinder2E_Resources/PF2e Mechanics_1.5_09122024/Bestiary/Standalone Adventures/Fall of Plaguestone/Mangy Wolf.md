---
title: "Mangy Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.v1HWnHIA77g8f5xg" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Mangy Wolf"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Mangy Wolf"
level: "Creature -1"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +4, Stealth: +4"
abilityMods: [1, 2, 0, -4, 1, -2]
speed: 35 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +4, __Ref__ +6, __Will__ +3"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+6 (finesse)\n__Damage__  1d6 + 1 piercing plus fleas"

  - name: "Fleas"
    desc: "  Anyone bitten by a mangy wolf is [[Conditions/Sickened|Sickened 1]] for 1 minute unless they succeed at a DC 14 Fortitude check save, but they can spend an Interact action to scratch away the fleas and remove the condition."
 
```

```encounter-table
name: Mangy Wolf
creatures:
  - 1: Mangy Wolf
```




