---
title: "Murshek"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Hqja6l76r7YKWxoX" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Murshek"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Murshek"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Draconic, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +13, Intimidation: +15, Nature: +15"
abilityMods: [4, 5, 4, 2, 1, 3]
speed: 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +17, __Will__ +11"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+1 Returning Spear, Leather Armor"
abilities_mid:
  - name: ""
  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (agile, nonlethal)\n__Damage__  1d4 + 8 bludgeoning"

  - name: "**Melee** `pf2:1` Spear"
    desc: "+15 ()\n__Damage__  1d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+16 (thrown 20 ft.)\n__Damage__  1d6 + 10 piercing"

  - name: "Intimidating Strike"
    desc: "`pf2:2`  Murshek makes a melee Strike. If she hits and deals damage, the target is [[Conditions/Frightened|Frightened 1]], or [[Conditions/Frightened|Frightened 2]] on a critical hit."

  - name: "Toxic Teamwork"
    desc: "  Murshek's attacks exacerbate any venom in her target's system. Against a creature affected by wyvern venom, her Strikes deal additional poison damage equal to twice the current stage of the wyvern venom affecting the target."

  - name: "Wingrider Trust"
    desc: "  Murshek and Xithnik operate as a team and verbally coordinate their actions. Xithnik has 3 actions, and Murshek does not need to spend any actions to command him."
 
```

```encounter-table
name: Murshek
creatures:
  - 1: Murshek
```




