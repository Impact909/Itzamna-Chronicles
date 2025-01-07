---
title: "Zdagren Half-Ear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Bil6tNI17HZplpOT" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Zdagren Half-Ear"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Zdagren Half-Ear"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Hallit, Orcish, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +18, Deception: +16, Diplomacy: +16, Intimidation: +14, Society: +14, Warfare Lore: +14"
abilityMods: [6, 1, 2, 2, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +13, __Ref__ +12, __Will__ +13; +1 to Will vs. auditory"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Orc Knuckle Dagger|+1 Striking Orc Knuckle Dagger]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "Half-Ear's Luck"
    desc: "`pf2:0`  **Frequency** once per day\n\n**Trigger** Zdagren takes a critical hit or critically fails a saving throw\n* * *\n\n**Effect** The critical hit becomes a normal hit, or the critical failure becomes a normal failure."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Knuckle Dagger"
    desc: "+19 (agile, disarm)\n__Damage__  2d6 + 8 piercing"

  - name: "Double Slice"
    desc: "`pf2:2`  Zdagren makes two Strikes against the same target, one with each of his knuckle daggers. Zdagren combines the damage of any attacks that hit and applies precision damage, resistances, and weaknesses only once. Both attacks count toward his multiple attack penalty, but the penalty increases only after both attacks."

  - name: "Formation Command"
    desc: "`pf2:1` (auditory) Each ally within 30 feet of Zdagren can Step, or Stride up to half their Speed. Each ally can benefit from Formation Command only once per round."
 
```

```encounter-table
name: Zdagren Half-Ear
creatures:
  - 1: Zdagren Half-Ear
```




