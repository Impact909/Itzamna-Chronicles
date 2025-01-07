---
title: "Lord Nar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1Jq80kKQvplwkmlV" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Lord Nar"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Lord Nar"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Diplomacy: +8, Intimidation: +8"
abilityMods: [5, 2, 3, -1, 1, 0]
speed: 30 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +8, __Will__ +9"
hp: 68
health:
  - name: ""
  - name: HP
    desc: "68"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|+1 Greatclub]], 2x [[Equipment/Hatchet|Hatchet]], [[Equipment/Hide Armor|Hide Armor]], Bronze Key"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` +1 Greatclub"
    desc: "+14 (backswing, shove)\n__Damage__  1d10 + 5 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+10 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 5 slashing"

  - name: "No Escape"
    desc: "`pf2:r`  **Trigger** An adjacent foe moves away.\n* * *\n\n**Effect** Lord Nar may move up to his speed but must end his move as close to the triggering creature as possible without entering the triggering creature's square."

  - name: "Rage"
    desc: "`pf2:1`  Lord Nar flies into a rage that lasts 1 minute and grants him 8 temporary Hit Points, 4 additional damage with his listed attacks, and a -1 penalty to AC.\n\nHe cannot use actions that have the concentrate trait while raging, unless they also have the rage trait.\n\nOnce his rage ends, Nar cannot Rage again for 1 minute.\n\n[[Feat_Feature Effects/Effect_ Rage|Effect: Rage]]"
 
```

```encounter-table
name: Lord Nar
creatures:
  - 1: Lord Nar
```




