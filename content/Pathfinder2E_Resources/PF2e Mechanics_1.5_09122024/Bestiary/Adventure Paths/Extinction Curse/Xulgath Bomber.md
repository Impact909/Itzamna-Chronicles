---
title: "Xulgath Bomber"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EIKxQmwDK2BujffE" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Xulgath Bomber"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #153: Life&#x27;s Long Shadows"
name: "Xulgath Bomber"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +14, Crafting: +17, Stealth: +15, Thievery: +15"
abilityMods: [3, 4, 1, 4, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder #153: Life&#x27;s Long Shadows_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +12, __Ref__ +17, __Will__ +15"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatpick|Greatpick]], 2x [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate) (Infused)]], 2x [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fire (Moderate) (Infused)]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Alchemist's Toolkit|Alchemist's Tools]], 2x Concentrated Xulgath Bile (Infused)"
  - name: "Infused Items"
    desc: "  A xulgath bomber carries the following infused items: 2 doses of concentrated xulgath bile, 2 [[Equipment/Acid Flask (Moderate)|Acid Flasks (Moderate)]], and 2 [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fires (Moderate)]]. These items last for 24 hours, or until the next time they make their daily preparations."

abilities_mid:
  - name: ""
  - name: "Powerful Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 24 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]], and on a critical failure, the creature is also [[Conditions/Slowed|Slowed 1]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stenches for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatpick"
    desc: "+16 (fatal d12)\n__Damage__  1d12 + 5 piercing plus concentrated-xulgath-bile"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 ()\n__Damage__  2d6 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, finesse)\n__Damage__  2d4 + 5 slashing"

  - name: "**Ranged** `pf2:1` Acid Flask"
    desc: "+17 (range increment 20 feet, splash)\n__Damage__  5 acid 2d6 + 2 acid 4 acid"

  - name: "**Ranged** `pf2:1` Alchemist&#x27;s Fire"
    desc: "+17 (range increment 20 feet, splash)\n__Damage__  2d8 + 2 fire 4 fire 4 fire"

  - name: "Concentrated Xulgath Bile"
    desc: " (poison) The [[Conditions/Sickened|Sickened]] condition from concentrated xulgath bile doesn't improve on its own until the target recovers from the poison. A target who recovers from concentrated xulgath bile is immune to being sickened by this poison for 1 minute\n\n**Saving Throw** DC 22 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d10 poison damage and [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** 2d10 poison damage and [[Conditions/Sickened|Sickened 2]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Sickened|Sickened 3]] (1 round)"

  - name: "Quick Bomber"
    desc: "`pf2:1`  The bomber Interacts to draw a bomb, then Strikes with it."
 
```

```encounter-table
name: Xulgath Bomber
creatures:
  - 1: Xulgath Bomber
```




