---
title: "Venexus's Wyrmling"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gWAK3Rf0BPADP0zO" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Venexus&#x27;s Wyrmling"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Venexus's Wyrmling"
level: "Creature 5"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[dragon]]
trait_04: [[evil]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Hallit"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +13, Intimidation: +10, Stealth: +12"
abilityMods: [5, 4, 2, -1, 1, 0]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +12, __Ref__ +15, __Will__ +9"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  cold,  paralyzed,  sleep; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Freezing Blood"
    desc: "`pf2:r` (arcane,cold) **Trigger** An adjacent creature deals piercing or slashing damage to the wyrmling\n* * *\n\n**Effect** The wyrmling's blood splatters onto the triggering creature, dealing 1d4 cold damage. A creature that takes cold damage in this way is [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 19 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Snow Vision"
    desc: "  Snow doesn't impair a white dragon's vision; the wyrmling ignores concealment from snowfall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (cold, magical)\n__Damage__  2d8 + 5 piercing 1d4 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, magical)\n__Damage__  2d6 + 5 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+13 (magical, reach 10 feet)\n__Damage__  2d8 + 5 bludgeoning"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,cold) The wyrmling breathes a cloud of frost that deals 6d6 cold damage in a 30-foot cone (DC 22 Reflex check). They can't use Breath Weapon again for 1d4 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The wyrmling makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  When the wyrmling scores a critical hit with a Strike, they recharge their Breath Weapon."

  - name: "Ice Climb"
    desc: "  A white dragon can climb on ice as though they had the listed climb Speed. They ignore difficult terrain and greater difficult terrain from ice and snow and don't risk falling when crossing ice."
 
```

```encounter-table
name: Venexus's Wyrmling
creatures:
  - 1: Venexus's Wyrmling
```




