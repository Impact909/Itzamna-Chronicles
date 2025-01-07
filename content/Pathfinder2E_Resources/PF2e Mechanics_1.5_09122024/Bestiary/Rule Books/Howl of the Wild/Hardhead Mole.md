---
title: "Hardhead Mole"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UHiBiX6uRijDG1yb" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Hardhead Mole"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Hardhead Mole"
level: "Creature 0"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +5, Stealth: +5, Survival: +6"
abilityMods: [2, 3, 3, -4, 2, 0]
speed: 20 feet,  burrow 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +5, __Ref__ +8, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Resistances__ bludgeoning 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Burrowing Retreat"
    desc: "`pf2:r`  **Trigger** The hardhead mole is hit by a Strike\n* * *\n\n**Effect** The hardhead mole immediately Burrows to a burrow hole if there is one within 20 feet. This movement doesn't trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+4 ()\n__Damage__  1d6 + 2 piercing"

  - name: "Shovel Earth"
    desc: "`pf2:1` (manipulate) The hardhead mole leaves a burrow hole in its square or an adjacent square. The square becomes difficult terrain but can be flattened back into normal terrain with an Interact action."

  - name: "Unbalancing Burrow"
    desc: "`pf2:2` (move) The hardhead mole Burrows up to 20 feet in a straight line, displacing the earth on the surface. Any creature it passes through takes 1d6 bludgeoning damage (DC 14 Reflex check save). On a failed save, a creature is knocked [[Conditions/Prone|Prone]]. This creates a burrow hole at the beginning and end of the line."
 
```

```encounter-table
name: Hardhead Mole
creatures:
  - 1: Hardhead Mole
```




