---
title: "Corrupted Retainer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QkAvjiqYiRlJYWKe" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Corrupted Retainer"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Corrupted Retainer"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +6, Survival: +6"
abilityMods: [2, 2, 3, 0, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 19
armorclass:
  - name: AC
    desc: "19 21 with shield raised; __Fort__ +9, __Ref__ +6, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Trident|Trident]], [[Equipment/Wooden Shield|Wooden Shield]], [[Equipment/Hide Armor|Hide Armor]], [[Equipment/Clothing (Ordinary)|Gray Robes]]"
abilities_mid:
  - name: ""
  - name: "No Escape"
    desc: "`pf2:r` (rage) **Trigger** A foe within the corrupted retainer's reach attempts to move away from them\n* * *\n\n**Effect** The corrupted retainer keeps pace with the triggering foe. The corrupted retainer Strides up to their Speed, following that foe and keeping it in reach throughout its movement until it stops moving or the corrupted retainer has moved their full Speed."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+11 (thrown 20 ft., fatal d10)\n__Damage__  1d8 + 2 piercing"

  - name: "Demonic Strength"
    desc: "  Corrupted retainers deal an extra 1d8 damage with their tridents, and any trident gains the fatal d10 trait while the corrupted retainer is using it (both the extra weapon damage die and the fatal trait have already been included in the corrupted retainer's trident Strike above)."

  - name: "Tainted Rage"
    desc: "`pf2:1` (concentrate,emotion,mental) The corrupted retainer begins to rage and gains 5 temporary Hit Points. The rage lasts for 1 minute or until they fall unconscious, whichever happens first. While raging, the corrupted retainer deals 2 additional damage with melee weapons, has a -1 penalty to AC, and cannot use actions that have the concentrate trait unless those actions also have the rage trait. The corrupted retainer can still [[Actions/Seek|Seek]] while raging.\n\n[[Feat_Feature Effects/Effect_ Rage|Effect: Rage]]"
 
```

```encounter-table
name: Corrupted Retainer
creatures:
  - 1: Corrupted Retainer
```


Human hirelings


