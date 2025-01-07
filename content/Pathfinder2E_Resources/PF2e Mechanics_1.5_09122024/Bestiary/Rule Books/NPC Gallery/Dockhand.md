---
title: "Dockhand"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2bz6UXYz8iSb4tYi" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Dockhand"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Dockhand"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +3, Athletics: +5, Intimidation: +3, Labor Lore: +4"
abilityMods: [3, 1, 3, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +7, __Ref__ +5, __Will__ +3"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Leather Armor|Leather Armor]], 3x Empty Bottle, [[Equipment/Alcohol|Whiskey]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal)\n__Damage__  1d4 + 3 bludgeoning"

  - name: "**Ranged** `pf2:1` Bottle"
    desc: "+5 (agile, thrown 20 ft.)\n__Damage__  1d6 + 3 bludgeoning"

  - name: "Heft Crate"
    desc: "`pf2:2` (manipulate) **Requirements** The dockhand is adjacent to a crate\n* * *\n\n**Effect** The dockhand picks up a crate and heaves it up to 15 feet. Upon landing, the crate breaks open in a 5-foot burst. Each creature within the area takes 2d6 bludgeoning damage (DC 13 Reflex check save), and the area becomes difficult terrain until cleared."

  - name: "Swig"
    desc: "`pf2:2` (manipulate) The dockhand Interacts to either draw a bottle of [[Equipment/Alcohol|Alcohol]] or pick up a nearby unattended bottle of alcohol and drink the whole thing.\n\nFor 1 minute, the dockhand gains a +2 item bonus to melee damage rolls and saving throws against fear, but they become [[Conditions/Clumsy|Clumsy 1]]."
 
```

```encounter-table
name: Dockhand
creatures:
  - 1: Dockhand
```



Working to load and unload cargo from ships, dockhands are considered unruly, but many stay focused and work hard until the job is done. Some do celebrate the end of their work day with rowdy drinking.

* * *

Every day, laborers perform backbreaking physical work.
