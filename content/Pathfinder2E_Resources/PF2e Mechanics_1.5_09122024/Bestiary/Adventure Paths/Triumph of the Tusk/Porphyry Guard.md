---
title: "Porphyry Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.e05La0fnotymv51P" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Porphyry Guard"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Porphyry Guard"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Orcish, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +11, Crafting: +10, Intimidation: +10, Survival: +10, Blisterwell Lore: +12"
abilityMods: [4, 3, 5, 1, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +10, __Will__ +12"
hp: 82
health:
  - name: ""
  - name: HP
    desc: "82; __Resistances__ slashing 4"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|Battle Axe]], [[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Chain Mail|Chain Mail]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+14 (sweep)\n__Damage__  1d8 + 8 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+15 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 6 piercing"

  - name: "Double Shot"
    desc: "`pf2:1`  The porphyry guard makes two longbow Strikes targeting two different creatures within the longbow's first range increment. Both Strikes uses the guard's current multiple attack penalty, but each strike takes a –2 penalty."

  - name: "Weapon Master"
    desc: "  The porphyry guard has access to the critical specialization effects of any weapons they wield."
 
```

```encounter-table
name: Porphyry Guard
creatures:
  - 1: Porphyry Guard
```




