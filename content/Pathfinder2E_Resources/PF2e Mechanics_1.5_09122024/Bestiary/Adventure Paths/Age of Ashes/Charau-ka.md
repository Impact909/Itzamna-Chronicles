---
title: "Charau-ka"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L6MiNmIcSk4GEPcP" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/charau-ka
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Charau-ka"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #145: Hellknight Hill"
name: "Charau-ka"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[charau-ka]]
trait_03: [[evil]]
trait_04: [[humanoid]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic, Mwangi"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Religion: +4, Stealth: +6"
abilityMods: [3, 3, 2, -1, 1, 0]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #145: Hellknight Hill_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +8, __Will__ +4"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sickle|Sickle]], [[Equipment/Whip|Whip]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+8 (agile, finesse, trip)\n__Damage__  1d4 + 3 slashing"

  - name: "**Melee** `pf2:1` Whip"
    desc: "+8 (disarm, finesse, nonlethal, reach, trip)\n__Damage__  1d4 + 3 slashing"

  - name: "**Ranged** `pf2:1` Thrown Debris"
    desc: "+8 (thrown 20 ft., deadly d6)\n__Damage__  1d6 + 3 bludgeoning"

  - name: "Shrieking Frenzy"
    desc: " (primal) **Trigger** The charau-ka's turn begins.\n\n**Frequency** once per hour\n* * *\n\n**Effect** The charau-ka is [[Conditions/Quickened|Quickened]] until the end of its turn, and can use the extra action to Stride or Strike. Due to its loud wailing while in a shrieking frenzy, the charau-ka can't speak and automatically critically fails all Stealth checks."

  - name: "Thrown Weapon Mastery"
    desc: "  When a charau-ka throws a weapon, the weapon gains the deadly d6 weapon trait. When it throws an improvised weapon, it doesn't take the -2 penalty for using an improvised weapon, nor does it take the penalty for using that weapon to make a lethal attack instead of a nonlethal attack."
 
```

```encounter-table
name: Charau-ka
creatures:
  - 1: Charau-ka
```




