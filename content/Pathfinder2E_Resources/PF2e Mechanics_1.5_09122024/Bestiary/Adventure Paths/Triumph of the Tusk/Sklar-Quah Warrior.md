---
title: "Sklar-Quah Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AzDTjjfnrEKUaG2b" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Sklar-Quah Warrior"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Sklar-Quah Warrior"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; "
languages: "Common, Orcish, Shoanti, Varisian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +19, Intimidation: +18, Nature: +15"
abilityMods: [5, 3, 2, 1, 1, 3]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +15, __Ref__ +16, __Will__ +13"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|+1 Striking Battle Axe]], [[Equipment/Composite Shortbow|Composite Shortbow]], 2x [[Equipment/Hatchet|Hatchet]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Counting Coup"
    desc: "`pf2:r`  **Trigger** An enemy moves within the Sklar-Quah warrior's reach\n* * *\n\n**Effect** The Sklar-Quah warrior swings their weapon as close to their enemy as they can without touching them, immediately attempting a [[Actions/Demoralize|Demoralize]] check. On a success, the enemy is [[Conditions/Off-Guard|Off-Guard]] until the beginning of their next turn."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+20 (magical, sweep)\n__Damage__  2d10 + 9 slashing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+19 (agile, sweep)\n__Damage__  2d8 + 9 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+18 (agile, sweep, thrown 10 ft.)\n__Damage__  2d8 + 9 slashing"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+18 (deadly d10, propulsive, range increment 60 feet, reload 0)\n__Damage__  2d6 + 8 piercing"

  - name: "Guerrilla Tactics"
    desc: "`pf2:1`  **Requirements** The Sklar-Quah warrior is holding their hatchet\n* * *\n\n**Effect** The Sklar-Quah warrior makes a ranged Strike with their hatchet and then draws their battle axe."
 
```

```encounter-table
name: Sklar-Quah Warrior
creatures:
  - 1: Sklar-Quah Warrior
```




