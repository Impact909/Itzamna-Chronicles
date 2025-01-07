---
title: "Bloody Berleth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2jmTPJnqRqF5KJgh" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Bloody Berleth"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Bloody Berleth"
level: "Creature 11"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Low-Light Vision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Deception: +22, Diplomacy: +18, Intimidation: +22, Stealth: +17, Gang Lore: +18"
abilityMods: [5, 2, 4, 1, 1, 3]
speed: 20 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +23, __Ref__ +21, __Will__ +20"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Scythe|+1 Striking Shovel]], [[Equipment/Glue Bomb (Moderate)|Tanglefoot Bag (Moderate)]], [[Equipment/Chain Mail|Chain Mail]], [[Equipment/Ring of Lies|Ring of Lies]], [[Equipment/Elixir of Life (Moderate)|Elixir of Life (Moderate)]], 4x [[Equipment/Spellstrike Ammunition (Type III)|Spellstrike Ammunition (Type III) (Blindness) (DC 24)]], [[Equipment/Juggernaut Mutagen (Greater)|Juggernaut Mutagen (Greater)]], [[Equipment/Smoke Ball (Greater)|Smokestick (Greater)]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shovel"
    desc: "+24 (deadly d10, magical, trip)\n__Damage__  2d10 + 11 slashing"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+19 (range increment 120 feet, reload 2)\n__Damage__  1d10 piercing"

  - name: "Concussive Beatdown"
    desc: "`pf2:1`  **Requirements** Berleth has just used his shovel to Trip a creature\n* * *\n\n**Effect** Berleth brutally brings his shovel down on the prone foe, making a shovel Strike. On a hit, the Strike deals damage as normal, plus the target must make a DC 30 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 2]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 1]] for 1 minute."

  - name: "Decapitate"
    desc: "`pf2:2`  Berleth plunges his shovel through a creature's neck as though it were peat moss.\n\nHe makes a shovel Strike against an adjacent [[Conditions/Unconscious|Unconscious]] or [[Conditions/Immobilized|Immobilized]] creature. On a hit, the creature is [[Conditions/Wounded|Wounded 2]] (possibly [[Conditions/Dying|Dying]])."

  - name: "Final Blow"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** Berleth is reduced to 0 HP\n* * *\n\n**Effect** Berleth makes a final shovel Strike before dying."
 
```

```encounter-table
name: Bloody Berleth
creatures:
  - 1: Bloody Berleth
```




