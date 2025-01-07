---
title: "Reckless Scientist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.96phAW2orNsPnzt8" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Reckless Scientist"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Reckless Scientist"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Crafting: +17, Deception: +9, Medicine: +10, Stealth: +12, Engineering Lore: +15, Underworld Lore: +13"
abilityMods: [1, 4, 5, 5, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +17, __Ref__ +14, __Will__ +10; +1 status to all saves vs. poison"
hp: 92
health:
  - name: ""
  - name: HP
    desc: "92; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sickle|+1 Sickle]], 2x [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate) (Infused)]], 2x [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fire (Moderate) (Infused)]], 2x [[Equipment/Frost Vial (Moderate)|Frost Vial (Moderate) (Infused)]], [[Equipment/Padded Armor|Work Coat]], [[Equipment/Alchemist's Toolkit|Alchemist's Tools]], [[Compendium.pf2e.equipment-srd.Item.HamOU17sqb5ljiB5|Bandolier]], [[Equipment/Antidote (Moderate)|Antidote (Moderate)]], [[Equipment/Antiplague (Moderate)|Antiplague (Moderate)]], [[Equipment/Bomber's Eye Elixir (Lesser)|Bomber's Eye Elixir (Lesser) (Infused)]], 3x [[Equipment/Elixir of Life (Lesser)|Elixir of Life (Lesser) (Infused)]]"
  - name: "Infused Items"
    desc: "  A reckless scientist carries the following infused items:\n\n*   2 [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate)]],\n*   2 [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fire (Moderate)]],\n*   1 [[Equipment/Bomber's Eye Elixir (Lesser)|Bomber's Eye Elixir (Lesser)]],\n*   2 [[Equipment/Frost Vial (Moderate)|Frost Vial (Moderate)]],\n*   3 [[Equipment/Elixir of Life (Lesser)|Elixir of Life (Lesser)]]\n\nThese items last for 24 hours, or until the next time the scientist makes their daily preparations."

abilities_mid:
  - name: ""
  - name: "Unstable Compounds"
    desc: "  When an attacker scores a critical hit against the reckless scientist, one of the scientist's poorly stowed alchemical items bursts. The GM determines the item randomly. If it was a bomb, the alchemist takes damage from the bomb, and any creature adjacent to the alchemist takes the splash damage. Any other item is simply wasted."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+17 (agile, finesse, magical, trip)\n__Damage__  1d4 + 7 slashing"

  - name: "**Ranged** `pf2:1` Moderate Acid Flask"
    desc: "+16 (range increment 20 feet, splash)\n__Damage__  1 acid 2d6 acid 2 acid"

  - name: "**Ranged** `pf2:1` Moderate Alchemist&#x27;s Fire"
    desc: "+16 (range increment 20 feet, splash)\n__Damage__  2d8 fire 2 fire 2 fire"

  - name: "**Ranged** `pf2:1` Moderate Frost Vial"
    desc: "+16 (range increment 20 feet, splash)\n__Damage__  2d6 cold 2 cold"

  - name: "Quick Bomber"
    desc: "`pf2:1`  The reckless scientist [[Actions/Interact|Interact]] to draw a bomb, then Strikes with it."

  - name: "Reckless Alchemy"
    desc: "`pf2:1` (concentrate,manipulate) **Requirements** The reckless scientist is holding a bomb or elixir\n* * *\n\n**Effect** The reckless scientist combines the bomb with another bomb or the elixir with another elixir. They can [[Actions/Interact|Interact]] to draw a second bomb or elixir if necessary as part of this action. They attempt a DC 28 Crafting check check, destroying both component items to create one new item.\n\nIf a viable resulting item isn't used by the end of the scientist's next turn, it explodes as described under critical failure.\n* * *\n\n**Critical Success** The new item has the full effect of both component items when used.\n\n**Success** The new item combines both items, but halves the effect of each. (This halves damage for bombs, the amount of healing of elixirs of life, or the duration for effects that can't have their value halved. Details are determined by the GM.)\n\n**Failure** The new item is inert.\n\n**Critical Failure** The new item immediately explodes, dealing 3d6 piercing damage to the reckless scientist."
 
```

```encounter-table
name: Reckless Scientist
creatures:
  - 1: Reckless Scientist
```



It's the reckless scientist's job to break the rules of reality, no matter the cost.

* * *

Villains pursue selfish and cruel goals, trampling over anyone foolish or purehearted enough to stand in their way.
