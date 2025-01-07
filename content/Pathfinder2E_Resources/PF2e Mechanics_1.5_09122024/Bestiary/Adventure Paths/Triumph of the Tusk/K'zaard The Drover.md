---
title: "K'zaard The Drover"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rk9XHGStVGrIQnSe" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "K&#x27;zaard The Drover"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "K'zaard The Drover"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +11, Deception: +16, Diplomacy: +15, Stealth: +14, Thievery: +13"
abilityMods: [3, 6, 3, 5, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +11, __Ref__ +17, __Will__ +14"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Dagger, +1 Striking Orc Skewermaul, Leather Armor, Ring of Keys"
abilities_mid:
  - name: ""
  - name: "Back Pedal"
    desc: "`pf2:r`  **Trigger** K'zaard is targeted by a Strike\n* * *\n\n**Effect** K'zaard moves unpredictably and suddenly as he tries to dodge. He gains a +1 circumstance bonus against the triggering attack. After the attack is resolved, K'zaard can Step."

  - name: "Ferocity"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Skewermaul"
    desc: "+16 (brace, magical, two-hand d10, versatile p)\n__Damage__  2d6 + 6 bludgeoning"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+15 (agile, finesse, versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+15 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "Keep Talking"
    desc: "`pf2:1` (auditory,mental) K'zaard continues to speak quickly and convincingly. Creatures [[Conditions/Frightened|Frightened]] by K'zaard's Weaseling Words can't reduce the frightened condition caused by that effect at the end of their next turn."

  - name: "Sneak Attack"
    desc: "  K'zaard deals 2d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Weaseling Words"
    desc: "`pf2:2` (auditory,emotion,fear,mental) K'zaard weaves together a short speech that gives the listener pause. Enemies within 30 feet must attempt a DC 24 Will check save. While a creature is frightened by this ability, it's [[Conditions/Off-Guard|Off-Guard]] to K'zaard.\n* * *\n\n**Critical Success** No effect, and the creature is temporarily immune to Weaseling Words for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is uncertain and [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature is riddled with self-doubt about its own actions. It is [[Conditions/Frightened|Frightened 2]] and can't take hostile actions against K'zaard until the frightened condition ends."
 
```

```encounter-table
name: K'zaard The Drover
creatures:
  - 1: K'zaard The Drover
```




