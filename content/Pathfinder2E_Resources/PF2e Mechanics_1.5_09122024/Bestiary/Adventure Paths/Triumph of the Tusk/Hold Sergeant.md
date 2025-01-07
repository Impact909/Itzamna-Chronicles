---
title: "Hold Sergeant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M0lQP4zqSiLv17hx" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Hold Sergeant"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Hold Sergeant"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Intimidation: +11, Survival: +9"
abilityMods: [5, 2, 2, 0, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +9, __Will__ +13"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Falchion|Falchion]], 6x [[Equipment/Javelin|Javelin]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "Opportunistic Strike"
    desc: "`pf2:r`  **Trigger** A creature within the hold sergeant's melee reach is hit by a melee attack by one of the hold sergeant's allies\n* * *\n\n**Effect** The hold sergeant makes a Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Falchion"
    desc: "+15 (forceful, sweep)\n__Damage__  1d10 + 10 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+13 (thrown 30 ft.)\n__Damage__  1d6 + 10 piercing"

  - name: "Bark Orders"
    desc: "`pf2:1` (auditory,concentrate,emotion,mental) Bellowing mightily, the hold sergeant gives themself and all orc allies within 60 feet a +1 status bonus to attack and damage rolls until the start of the hold sergeant's next turn.\n\n[[Bestiary Effects/Effect_ Bark Orders (Hold Sergeant)|Effect: Bark Orders (Hold Sergeant)]]"
 
```

```encounter-table
name: Hold Sergeant
creatures:
  - 1: Hold Sergeant
```




