---
title: "Ship Captain"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XGuORSrmY9JLOgL7" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Ship Captain"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Ship Captain"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +12, Diplomacy: +11, Intimidation: +13, Survival: +10, Sailing Lore: +17"
abilityMods: [4, 2, 0, 1, 2, 3]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +12, __Will__ +14"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Rapier|+1 Rapier]], [[Equipment/Leather Armor|Leather Armor]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Bravery"
    desc: "  When the Ship Captain rolls a success on a Will save against a fear effect, they get a critical success instead. In addition, any time they gain the [[Conditions/Frightened|Frightened]] condition, reduce its value by 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+17 (deadly d8, disarm, magical)\n__Damage__  1d6 + 10 piercing"

  - name: "**Melee** `pf2:1` Main-Gauche"
    desc: "+16 (agile, disarm, parry, versatile s)\n__Damage__  1d4 + 10 piercing"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+14 (range increment 60 feet, reload 1)\n__Damage__  1d6 + 6 piercing"

  - name: "Dual Disarm"
    desc: "`pf2:2`  The captain makes two Strikes, one with their rapier and one with their main-gauche (in either order). If both Strikes hit, the ship captain can attempt to [[Actions/Disarm|Disarm]] the target.\n\nTheir multiple attack penalty increases only after all the attacks are made."

  - name: "No Quarter!"
    desc: "`pf2:1` (auditory,concentrate,emotion,linguistic,mental) The captain orders their shipmates to fight without mercy. All allied creatures of equal or lower level within 20 feet of the ship captain gain a+1 status bonus to attack rolls and damage rolls until the end of the ship captain's next turn.\n\n[[Bestiary Effects/Effect_ No Quarter!|Effect: No Quarter!]]"
 
```

```encounter-table
name: Ship Captain
creatures:
  - 1: Ship Captain
```



The captain is the ultimate authority on a vessel, responsible for the livelihood and well-being of everyone on the ship.

* * *

Adventurers may need passage on a swift vessel, or they might face danger from raiders at sea or in coastal settlements.
