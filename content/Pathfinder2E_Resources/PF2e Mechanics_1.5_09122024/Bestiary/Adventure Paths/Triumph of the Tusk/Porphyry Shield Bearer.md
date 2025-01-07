---
title: "Porphyry Shield Bearer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SYu2xuwKxwZbK4k7" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Porphyry Shield Bearer"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Porphyry Shield Bearer"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Orcish, Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Intimidation: +10, Society: +11"
abilityMods: [4, 2, 5, 2, 3, 0]
speed: 20 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +9, __Will__ +14"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hatchet|Hatchet]], [[Equipment/Shield Spikes|Shield Spikes]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Half Plate|Half Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "Shield Warden"
    desc: "  When the shield bearer has their shield raised, they can Shield Block when an attack is made against an adjacent ally. If they do, the shield prevents that ally from taking damage instead of the shield bearer."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hatchet"
    desc: "+15 (agile, sweep)\n__Damage__  1d6 + 10 slashing"

  - name: "**Ranged** `pf2:1` Hatchet"
    desc: "+15 (agile, sweep, thrown 10 ft.)\n__Damage__  1d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Shield Spikes"
    desc: "+15 ()\n__Damage__  1d6 + 10 slashing"

  - name: "Offensive Block"
    desc: "`pf2:2`  The shield bearer can Step, make a shield spikes Strike, and Raise their Shield in any order."

  - name: "Retributive Bash"
    desc: "  The porphyry shield bearer deals an additional 1d8 damage with weapon Strikes against any creature that has damaged the shield bearer or an adjacent ally since the beginning of the shield bearer's last turn."

  - name: "Tenacious Shield"
    desc: "  **Frequency** once per day\n\n**Trigger** The shield bearer's shield would be destroyed\n* * *\n\n**Effect** The shield is not destroyed and its Hit Points are instead reduced to 5."
 
```

```encounter-table
name: Porphyry Shield Bearer
creatures:
  - 1: Porphyry Shield Bearer
```




