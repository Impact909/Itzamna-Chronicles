---
title: "Uthul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L3jAUkNcdLyPGzsC" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Uthul"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Uthul"
level: "Creature 14"

alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[chaotic]]
trait_03: [[elemental]]
trait_04: [[evil]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +27, Intimidation: +23, Stealth: +25"
abilityMods: [7, 7, 4, -1, -2, 3]
speed:  fly 100 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +29, __Will__ +22"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Immunities__  electricity,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "High Winds"
    desc: " (air,aura) 40 feet. Air in the aura is difficult terrain for Flying creatures without the air trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile)\n__Damage__  3d12 + 11 slashing"

  - name: "**Ranged** `pf2:1` Debris"
    desc: "+29 (range increment 60 feet)\n__Damage__  5d8 + 15 bludgeoning"

  - name: "Lightning Crash"
    desc: "`pf2:1` (electricity,incapacitation,sonic) The uthul unleashes a powerful bolt of lightning and a stunning thunderclap. The bolt deals 6d12 electricity damage to all creatures in a 30-foot line, with a DC 34 Reflex check save, and every creature in a 20-foot emanation must attempt a DC 34 Fortitude check save.\n\nThe uthul can't use Lightning Crash again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned]] for 1 round.\n\n**Critical Failure** The creature is stunned for 1d4 rounds."

  - name: "Swiftness"
    desc: "  An uthul's movement doesn't trigger reactions."

  - name: "Whirlwind Form"
    desc: "`pf2:2` (concentrate) The uthul transforms itself into a swirling vortex of storm and fury 10 feet wide and up to 40 feet tall. It stays in this form for 3 rounds or until it Dismisses the effect. While in this form, the uthul gains resistance 10 to physical damage and can move through other creatures.\n\nIts aura remains active, but it can't make debris Strikes nor use Lightning Crash. Instead, any creature the uthul moves through takes 4d6 bludgeoning + 2d12 electricity damage. A creature can take this damage only once per round. A Large or smaller creature must also succeed at a DC 32 Reflex check save or be picked up and held suspended within the vortex. Suspended creatures move with the uthul. A creature can attempt to escape by spending an action to attempt a DC 32 Reflex check save (or a Acrobatics check to maneuver in flight if it has a fly Speed). Upon escaping, or when the uthul transforms back into its storm cloud form, a suspended creature is hurled 1d4 x 10 feet in a random direction, then falls unless it can fly or otherwise remain aloft.\n\nAfter returning to its normal form, the uthul must wait 1 minute before it can use Whirlwind Form again.\n\n[[Bestiary Effects/Effect_ Whirlwind Form|Effect: Whirlwind Form]]"
 
```

```encounter-table
name: Uthul
creatures:
  - 1: Uthul
```



An uthul most often appears to be a dark, swirling cloud filled with flying debris and streaked with sudden flashes of lightning. Although they are clearly elemental in nature, uthuls are nearly always found on the Material Plane, where they hide among natural cloud formations, especially thunderstorms.
