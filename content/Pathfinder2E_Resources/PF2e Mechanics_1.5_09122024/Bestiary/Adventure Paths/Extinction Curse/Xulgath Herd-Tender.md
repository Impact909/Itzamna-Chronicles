---
title: "Xulgath Herd-Tender"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.65bRleEgzlPKEvAg" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Xulgath Herd-Tender"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Xulgath Herd-Tender"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +18, Intimidation: +16, Nature: +17, Stealth: +16, Survival: +17, Dinosaur Lore: +11"
abilityMods: [4, 4, 2, -1, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +16, __Will__ +14"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x [[Equipment/Alchemist's Fire (Moderate)|Alchemist's Fire (Moderate)]], [[Equipment/Composite Shortbow|+1 Striking Composite Shortbow]], [[Equipment/Whip|Whip]], [[Equipment/Hide Armor|Hide Armor]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Mounted Defense"
    desc: "`pf2:r`  **Prerequisite** The herd-tender is mounted\n\n**Trigger** The herd-tender is targeted with a melee or ranged attack by an attacker they can see\n* * *\n\n**Effect** The herd-tender gains a +2 circumstance bonus to AC against the triggering attack."

  - name: "Powerful Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 26 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]], and on a critical failure, the creature is also [[Conditions/Slowed|Slowed 1]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stenches for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Whip"
    desc: "+19 (disarm, finesse, nonlethal, reach 10 feet, trip)\n__Damage__  1d4 + 10 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 ()\n__Damage__  2d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile)\n__Damage__  2d6 + 10 slashing"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+20 (deadly 2d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  2d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Alchemist&#x27;s Fire (Moderate)"
    desc: "+20 (bomb, range increment 20 feet, splash)\n__Damage__  2d8 fire 2 fire 2 fire"

  - name: "Feral Directive"
    desc: "`pf2:2`  The xulgath attempts to [[Actions/Command an Animal|Command an Animal]] on their mount, but instead of demanding a specific action such as Stride or Strike, the xulgath gives a general directive, such as to return to camp or to attack a small group the mount can see. The mount and the xulgath each retain 3 actions on their turns, but the mount doesn't change its general tactics until the xulgath uses Feral Directive or Command an Animal again."

  - name: "Mounted Superiority"
    desc: "  A mounted xulgath's Strikes deal an additional 1d8 damage to creatures that aren't mounted."
 
```

```encounter-table
name: Xulgath Herd-Tender
creatures:
  - 1: Xulgath Herd-Tender
```




