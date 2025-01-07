---
title: "Gristleburst"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lBtoTdi48FOt9m5b" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/goblin
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Gristleburst"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog"
name: "Gristleburst"
level: "Creature 2"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[goblin]]
trait_03: [[humanoid]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; "
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Crafting: +8, Intimidation: +6, Nature: +7, Stealth: +7, Survival: +7"
abilityMods: [0, 0, 0, 0, 0, 0]
speed: 25 feet
sourcebook: "_Pathfinder Blog_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +8, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30; __Resistances__ fire 1"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Alchemist's Toolkit|Alchemist's Tools]], [[Equipment/Formula Book (Blank)|Formula Scraps (as Formula Book)]], 2x Infused Reagents"
  - name: "Infused Items"
    desc: "  Gristleburst carries the following infused items, which last for 24 hours or until the next time he makes his daily preparations:\n\n[[Equipment/Acid Flask (Lesser)|Acid Flask (Lesser)]] (2)\n\n[[Equipment/Alchemist's Fire (Lesser)|Alchemist's Fire (Lesser)]] (4)\n\n[[Equipment/Eagle Eye Elixir (Lesser)|Eagle Eye Elixir (Lesser)]] (2)"

  - name: "Quick Bomber"
    desc: "`pf2:1`  Gristleburst draws an alchemical bomb with an Interact action and throws it as a ranged Strike."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+9 (agile, versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+11 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "**Ranged** `pf2:1` Lesser Alchemist&#x27;s Fire"
    desc: "+11 (alchemical, bomb, range increment 20 feet, splash)\n__Damage__  1d8 fire 1 fire 1 fire"

  - name: "**Ranged** `pf2:1` Lesser Acid Flask"
    desc: "+11 (alchemical, bomb, range increment 20 feet, splash)\n__Damage__  1 acid 1d6 acid 1 acid"

  - name: "Quick Smoke Bomb"
    desc: "  **Cost** 1 batch of infused reagents\n* * *\n\n**Effect** Gristleburst mixes up a short-lived lesser acid flask or lesser alchemist's fire without attempting a Crafting check. It remains potent only until the end of his next turn. When he throws this bomb, in addition to its normal effects, it creates a cloud of smoke in a 10-foot radius burst. Creatures in that area have the [[Conditions/Concealed|Concealed]] condition, and other creatures are concealed to them. This smoke lasts for 1 minute or until dissipated by a strong wind."
 
```

```encounter-table
name: Gristleburst
creatures:
  - 1: Gristleburst
```




