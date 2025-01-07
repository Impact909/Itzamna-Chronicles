---
title: "Tiger Lord"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RGKJcZVJvY6mCyaY" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Tiger Lord"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Tiger Lord"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Common, Hallit"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +18, Intimidation: +16"
abilityMods: [4, 2, 2, 0, 4, 2]
speed: 30 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +14, __Will__ +18"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|+1 Striking Battle Axe]], [[Equipment/Hatchet|Hatchet]], [[Equipment/Wooden Shield|Heavy Wooden Shield]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
  - name: "No Escape"
    desc: "`pf2:r`  **Trigger** A foe within reach attempts to move away from the Tiger Lord\n\n**Effect** The Tiger Lord Strides up to its Speed, following the foe and keeping it in reach throughout its movement until it stops moving or the Tiger Lord has moved its full Speed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+21 (magical, sweep)\n__Damage__  2d8 + 8 slashing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+21 (agile, sweep)\n__Damage__  1d6 + 8 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+21 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 8 slashing"

  - name: "Closing Volley"
    desc: "`pf2:3`  The Tiger Lord makes a ranged Strike with a hatchet, then Strides up to twice its speed. If it ends its movement within melee reach of the target of its ranged Strike, it may make a melee Strike against that enemy. If the ranged Strike hit the target, the target is [[Conditions/Off-Guard|Off-Guard]] against the melee Strike."

  - name: "Vengeful Rage"
    desc: "`pf2:r`  **Requirements** The Tiger Lord is not [[Conditions/Fatigued|Fatigued]] or already in a rage\n\n**Trigger** The Tiger Lord suffers damage that reduces its Hit Points to 100 or less.\n\n**Effect** The Tiger Lord flies into a rage that lasts 1 minute. While raging, the Tiger Lord gains a +1 status bonus to attack rolls, gains a +2 status bonus to damage rolls, and takes a -2 status penalty to AC. After the rage, the Tiger Lord is fatigued."
 
```

```encounter-table
name: Tiger Lord
creatures:
  - 1: Tiger Lord
```


Human barbarians


