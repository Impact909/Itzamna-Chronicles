---
title: "Blisterwell Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V6BuFBAmPsKNlaCE" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Blisterwell Warrior"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Blisterwell Warrior"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +10, Nature: +8, Survival: +10"
abilityMods: [5, 2, 3, 1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +10, __Will__ +10"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Pick|Pick]], 3x [[Equipment/Hatchet|Hatchet]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pick"
    desc: "+14 (fatal d10)\n__Damage__  1d6 + 9 piercing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+12 (thrown 10 ft.)\n__Damage__  1d6 + 9 slashing"

  - name: "Able Rider"
    desc: "`pf2:1`  The Blisterwell warrior Commands their mount, automatically succeeding at their check to control the animal. They then [[Actions/Raise a Shield|Raise their Shield]] or Draw a weapon."
 
```

```encounter-table
name: Blisterwell Warrior
creatures:
  - 1: Blisterwell Warrior
```




