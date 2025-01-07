---
title: "Corrupt Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Z1dn6vzszhGHhG4W" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Corrupt Guard"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Corrupt Guard"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Dwarven"
skills:
  - name: "Skills"
    desc: "Athletics: +25, Diplomacy: +19, Intimidation: +21, Society: +20, Stealth: +25"
abilityMods: [7, 3, 5, 0, 4, 1]
speed: 20 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +24, __Ref__ +20, __Will__ +21"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+1 Composite Shortbow]], [[Equipment/Maul|+1 Striking Maul]], [[Equipment/Breastplate|+1 Resilient Breastplate]], Key to Chiselrock's Prison, 50x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+28 (shove)\n__Damage__  2d12 + 15 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+25 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d8 + 8 piercing"

  - name: "Improved Knockdown"
    desc: "`pf2:2`  A corrupt guard can dash their foe to the ground with a single blow. They attempt a single melee Strike. If this Strike hits, they also apply the critical success effect of a Trip. If they used a two- handed melee weapon (such as a maul) for the Strike, they can use the weapon's damage die size instead of the regular die size for the damage from a critical Trip, and they ignore Trip's requirement to have a hand free."
 
```

```encounter-table
name: Corrupt Guard
creatures:
  - 1: Corrupt Guard
```




