---
title: "Druulbach"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wxwN2VM9YMiUgtmG" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Druulbach"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Druulbach"
level: "Creature 12"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[water]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Low-Light Vision"
languages: "Aklo, Common, Jotun, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +25, Intimidation: +22, Nature: +23, Religion: +23"
abilityMods: [7, 4, 5, 1, 5, 0]
speed: 35 feet,  swim 20 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +25, __Ref__ +20, __Will__ +23"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Resistances__ poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Sickle|+1 Striking Sickle]], [[Equipment/Leather Armor|+1 Leather Armor]], [[Equipment/Gorget of the Primal Roar|Gorget of the Primal Roar]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+26 (agile, finesse, magical, reach 10 feet, trip)\n__Damage__  1d10 poison 2d4 + 13 slashing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (agile, reach 10 feet)\n__Damage__  2d10 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+26 (primal, range 60 feet, water)\n__Damage__  8d6 bludgeoning"

  - name: "Occult Innate Spells"
    desc: "DC 29, attack +21; __5th __  _[[Spells/Mariner's Curse|Mariner's Curse]]_; __2nd __  _[[Spells/Augury|Augury]]_, _[[Spells/Mist|Mist]]_"

  - name: "Balanced Blades"
    desc: "  Druulbach's multiple attack penalty with agile weapons and agile unarmed attacks is –3 for his second attack and –6 for subsequent attacks (rather than –4 and –8)."

  - name: "Drowning Hook"
    desc: "`pf2:1` (primal,water) **Requirements** A creature is [[Conditions/Prone|Prone]] within Druulbach's reach\n* * *\n\n**Effect** Druulbach uses his sickle to push the creature down as water bubbles up below it. The target becomes submerged in water until they are no longer prone and must hold their breath if it can't breathe water. The target takes 6d6 bludgeoning damage (DC 29 Fortitude check) and loses 3 rounds worth of air if it fails the save."

  - name: "Flurry of Hooks"
    desc: "`pf2:2`  **Requirements** Druulbach is wielding two sickles\n* * *\n\n**Effect** Druulbach makes three sickle Strikes against one target. If multiple attacks hit, combine their damage and apply weaknesses and resistances only once."

  - name: "Serrated Takedown"
    desc: "`pf2:1`  **Requirements** Druulbach hit with a sickle Strike on his most recent action this turn\n* * *\n\n**Effect** Druulbach drags down the target, knocking it [[Conditions/Prone|Prone]] and dealing 3d6 persistent bleed damage to the creature."
 
```

```encounter-table
name: Druulbach
creatures:
  - 1: Druulbach
```


Male marsh giant ranger


