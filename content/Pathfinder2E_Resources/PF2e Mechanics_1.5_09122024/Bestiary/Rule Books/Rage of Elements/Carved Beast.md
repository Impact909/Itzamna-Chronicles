---
title: "Carved Beast"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a4t6GpwGLImML6iC" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Carved Beast"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Carved Beast"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15, Nature: +15, Stealth: +16"
abilityMods: [2, 4, 3, 0, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 22
armorclass:
  - name: AC
    desc: "22 (24 while Dug In); __Fort__ +13, __Ref__ +9, __Will__ +17"
hp: 92
health:
  - name: ""
  - name: HP
    desc: "92; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ axe vulnerability 5, fire 10"
abilities_top:
  - name: ""

  - name: "Top-Heavy"
    desc: "  While the carved beast is not Dug In, its unwieldy design leaves it vulnerable to falling over. The DC of any attempt to knock the carved beast [[Conditions/Prone|Prone]] is reduced by 5, and the beast takes a –5 status penalty to any check or save it attempts to resist being knocked prone. Additionally, whenever the beast fails to [[Actions/Trip|Trip]] opponents with its roots Strike, it critically fails instead. If successfully Shoved by an opponent, the beast must succeed at a DC 20 Reflex check save or fall prone."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Statue"
    desc: "+15 (shove)\n__Damage__  2d8 + 5 bludgeoning plus knockdown"

  - name: "**Melee** `pf2:1` Roots"
    desc: "+17 (finesse, trip)\n__Damage__  2d8 + 5 bludgeoning"

  - name: "Dig In"
    desc: "`pf2:1`  The carved beast digs its roots into the ground for better protection and purchase. While Dug In, the carved beast can't Stride nor use its roots Strike; however, this also negates the effects of top-heavy, grants the beast a +2 status bonus to its AC and Fortitude saves, and increases the damage of its statue Strike by 1d8. The carved beast can spend an action on its turn to end the effect; alternatively, the effect ends when the carved beast is moved by force, such as via a successful [[Actions/Shove|Shove]] attack."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Carved Beast
creatures:
  - 1: Carved Beast
```



An untold number of stumps carved into roughly hewn animal shapes roam the Plane of Wood. The statue portion of these carved beasts is incapable of articulated movement, though the living wood at their base is fully animate. When left to their own devices, carved beasts prefer to roughly mimic the behaviors of the animals they resemble, like children playing with inarticulate toys.
