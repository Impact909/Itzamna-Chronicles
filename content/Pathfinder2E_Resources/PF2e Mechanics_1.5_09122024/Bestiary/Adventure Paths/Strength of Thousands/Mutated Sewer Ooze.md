---
title: "Mutated Sewer Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uLYHJN2Uv6STJRCg" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/mutant
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Mutated Sewer Ooze"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #170: Spoken on the Song Wind"
name: "Mutated Sewer Ooze"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[mutant]]
trait_03: [[ooze]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +9"
abilityMods: [5, -2, 4, -5, 0, -5]
speed: 10 feet
sourcebook: "_Pathfinder #170: Spoken on the Song Wind_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +16, __Ref__ +8, __Will__ +10"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Motion Sense 60 feet"
    desc: "  A sewer ooze can sense nearby motion through vibration and air movements."

  - name: "Noxious Scent"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 23 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure). A creature taking persistent acid damage from the ooze's pseudopod can't recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+17 (agile, deadly d10, finesse, versatile s)\n__Damage__  2d8 + 5 bludgeoning 1d4 acid 1d4 acid"

  - name: "Filth Wave"
    desc: "`pf2:1`  **Frequency** once per minute\n* * *\n\n**Effect** The sewer ooze unleashes a wave of filth, covering all creatures within a 20-foot emanation. Each creature in the area must succeed at a DC 24 Reflex check save or take 1d4 acid damage and a -10-foot penalty to its Speeds for 1 minute (on a critical failure, the creature also falls [[Conditions/Prone|Prone]]). A creature can spend an Interact action to clean someone off, decreasing the Speed penalty by 5 feet with each action.\n\n[[Bestiary Effects/Effect_ Filth Wave|Effect: Filth Wave]]"
 
```

```encounter-table
name: Mutated Sewer Ooze
creatures:
  - 1: Mutated Sewer Ooze
```




