---
title: "Aspis Technician"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gEGVDM6Vjg3nzRne" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/gnome
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Aspis Technician"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Slithering"
name: "Aspis Technician"
level: "Creature 7"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[gnome]]
trait_04: [[humanoid]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: "Common, Fey, Gnomish, Mwangi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Arcana: +15, Crafting: +17, Stealth: +15, Thievery: +15, Aspis Consortium Lore: +15"
abilityMods: [1, 4, 2, 4, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: The Slithering_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +17, __Will__ +15"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Rapier|+1 Striking Rapier]], 2x [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate)]], 2x [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fire (Moderate)]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], Bronze Aspis Consortium Badge, [[Equipment/Alchemist's Toolkit|Alchemist's Tools Expanded]], [[Equipment/Bomber's Eye Elixir (Lesser)|Bomber's Eye Elixir (Lesser)]], [[Equipment/Cheetah's Elixir (Moderate)|Cheetah's Elixir (Moderate)]], 2x [[Equipment/Spider Venom|Hunting Spider Venom]], 2x [[Equipment/Antidote (Lesser)|Antidote (Lesser)]], 2x [[Equipment/Elixir of Life (Lesser)|Elixir of Life (Lesser)]]"
  - name: "Infused Items"
    desc: "  An Aspis technician carries the following infused items:\n\n*   2 - [[Equipment/Antidote (Lesser)|Lesser Antidotes]]\n*   2 - [[Equipment/Acid Flask (Moderate)|Moderate Acid Flasks]]\n*   2 - [[Equipment/Alchemist's Fire (Moderate)|Moderate Alchemist's Fires]]\n*   2 - [[Equipment/Elixir of Life (Lesser)|Lesser Elixirs of Life]]\n\nThese items last for 24 hours or until the next time the technician makes their daily preparations."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+18 (deadly d8, disarm, finesse)\n__Damage__  2d6 + 8 piercing plus hunting-spider-venom"

  - name: "**Ranged** `pf2:1` Acid Flask"
    desc: "+18 (range increment 20 feet, splash)\n__Damage__  5 acid 2d6 + 2 acid 4 acid"

  - name: "**Ranged** `pf2:1` Alchemist&#x27;s Fire"
    desc: "+18 (range increment 20 feet, splash)\n__Damage__  2d8 + 2 fire 4 fire 4 fire"

  - name: "Hunting Spider Venom"
    desc: " (poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d10 poison and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d12 poison, [[Conditions/Clumsy|Clumsy 1]], and off-guard (1 round)\n\n**Stage 3** 2d6 poison, [[Conditions/Clumsy|Clumsy 2]], and off-guard (1 round)"

  - name: "Poison Weapon"
    desc: "`pf2:1` (manipulate) **Requirements** The Aspis technician is wielding a piercing or slashing weapon and has a free hand\n* * *\n\n**Effect** The Aspis technician applies a poison to the weapon."

  - name: "Quick Bomber"
    desc: "`pf2:1`  The Aspis technician Interacts to draw a bomb, then Strikes with it."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The Aspis technician deals an extra 2d6 precision precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Aspis Technician
creatures:
  - 1: Aspis Technician
```




