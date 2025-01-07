---
title: "Black Whale Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PJolCFVnS5bFoWbw" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Black Whale Guard"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Black Whale Guard"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +24, Games Lore: +17"
abilityMods: [5, 3, 5, -1, 0, 4]
speed: 20 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +23, __Ref__ +21, __Will__ +18"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Shortbow, [[Equipment/Club|Club]], [[Equipment/Nightmare Cudgel|Nightmare Cudgel]], Chain Mail, 2x [[Equipment/Storm Arrow|Storm Arrow]], 40x Arrows"
abilities_mid:
  - name: ""
  - name: "No Escape"
    desc: "`pf2:r`  **Trigger** An enemy within reach of the Black Whale guard attempts to move away\n* * *\n\n**Effect** The guard Strides up to their Speed, following the enemy and keeping the enemy in reach throughout its movement until the enemy stops moving or the guard moves their full Speed."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Club"
    desc: "+24 (thrown 10 ft.)\n__Damage__  1d6 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Nightmare Cudgel"
    desc: "+25 (thrown 10 ft.)\n__Damage__  2d6 + 11 acid"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (agile, finesse, nonlethal, unarmed)\n__Damage__  1d4 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+22 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 + 6 piercing"

  - name: "Clobber"
    desc: "`pf2:1`  The guard makes a club Strike. On a hit, if the target is off-guard, the target must succeed at a DC 33 Fortitude check save or be stunned 2."

  - name: "Hammering Flurry"
    desc: "`pf2:2`  The guard makes three club Strikes against a single target, ignoring the multiple attack penalty until after all three attacks are completed."

  - name: "Shatter Defenses"
    desc: "`pf2:1` (press) **Requirements** A frightened creature is within melee reach of the Black Whale guard\n* * *\n\n**Effect** The guard makes a melee Strike against the frightened creature. If they hit and deal damage, the target becomes off-guard as long as it's frightened. If the target is already off-guard, it can't reduce its frightened value below 1 until the start of the guard's next turn."
 
```

```encounter-table
name: Black Whale Guard
creatures:
  - 1: Black Whale Guard
```




