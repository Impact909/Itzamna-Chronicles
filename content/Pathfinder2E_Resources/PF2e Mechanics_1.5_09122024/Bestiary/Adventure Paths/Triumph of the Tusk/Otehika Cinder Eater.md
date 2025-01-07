---
title: "Otehika Cinder Eater"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JW6ETcIuXCNP0GgM" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Otehika Cinder Eater"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Otehika Cinder Eater"
level: "Creature 9"
rare_03: [[Unique]]
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
    desc: "Acrobatics: +19, Athletics: +21, Intimidation: +20, Nature: +17"
abilityMods: [6, 4, 3, 1, 1, 3]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +18, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|+1 Striking Battle Axe]], [[Equipment/Composite Shortbow|Composite Shortbow]], 2x [[Equipment/Hatchet|Hatchet]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Counting Coup"
    desc: "`pf2:r`  **Trigger** An enemy moves within Otehika's reach\n* * *\n\n**Effect** Otehika swings their weapon as close to their enemy as they can without touching them, immediately attempting a [[Actions/Demoralize|Demoralize]] check. On a success, the enemy is [[Conditions/Off-Guard|Off-Guard]] until the beginning of their next turn."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+21 (magical, sweep)\n__Damage__  2d10 + 11 slashing"

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+20 (agile, sweep)\n__Damage__  2d8 + 11 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+19 (agile, sweep, thrown 10 ft.)\n__Damage__  2d8 + 11 slashing"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+19 (deadly d10, propulsive, range increment 60 feet, reload 0)\n__Damage__  2d6 + 9 piercing"

  - name: "Twin Takedown"
    desc: "`pf2:1`  **Frequency** once per round\n\n**Requirements** Otehika wields two melee weapons, each in a different hand.\n* * *\n\n**Effect** Otehika makes two Strikes against their target, one with each of the required weapons. If both hit the same target, combine the damage from the weapons for the purpose of resistances and weaknesses. They apply their multiple attack penalty to each Strike normally."
 
```

```encounter-table
name: Otehika Cinder Eater
creatures:
  - 1: Otehika Cinder Eater
```




