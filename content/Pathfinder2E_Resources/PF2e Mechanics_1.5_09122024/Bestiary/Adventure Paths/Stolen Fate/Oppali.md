---
title: "Oppali"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5eUjLdW5lriCNKue" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Oppali"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #190: The Choosing"
name: "Oppali"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[plant]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +19, Stealth: +21"
abilityMods: [5, 7, 3, -4, 3, -1]
speed: 20 feet
sourcebook: "_Pathfinder #190: The Choosing_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +19, __Ref__ +21, __Will__ +17"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "Soundsense (Precise) 60 feet"
    desc: "  An oppali's sense of hearing is a precise sense to a range of 60 feet."

abilities_mid:
  - name: ""
  - name: "Energizing Incompetence"
    desc: "`pf2:r`  **Trigger** A creature within 30 feet critically fails an attack against the oppali\n* * *\n\n**Effect** The attack instead becomes a failure, and the oppali becomes [[Conditions/Quickened|Quickened 1]] for 1 round. It can use this extra action to Step, Stride, or Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+23 (finesse, reach 15 feet, trip)\n__Damage__  2d8 + 11 bludgeoning plus drain-luck"

  - name: "**Ranged** `pf2:1` Staccato Blast"
    desc: "+23 (range 60 feet, sonic)\n__Damage__  6d6 sonic"

  - name: "Drain Luck"
    desc: " (mental,misfortune,primal) A creature other than an animal or plant hit by an oppali's vine Strike must attempt a DC 29 Fortitude check saving throw twice, taking the lower result as the actual result.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Drain Luck for 24 hours.\n\n**Success** The creature takes 2d6 poison damage. Until the start of the creature's next turn, the creature must roll twice and take the worse result on all checks.\n\n**Failure** The creature takes 2d6 persistent poison damage. For 1 round, the creature must roll twice and take the worse result on all checks.\n\n**Critical Failure** The creature takes 4d6 persistent poison damage. For 1 minute, the creature must roll twice and take the worse result on all checks."

  - name: "Trumpet Blast"
    desc: "`pf2:2` (primal,sonic) The oppali emits a massive blast of discordant noise that deals 9d8 sonic damage to creatures within a 60-foot cone (DC 29 Fortitude check). Creatures who fail the save are also [[Conditions/Deafened|Deafened]] for 1 round. The oppali can't use its Trumpet Blast again for 1d4 rounds or until it takes at least 20 points of sonic damage from a single source (whichever comes first)."
 
```

```encounter-table
name: Oppali
creatures:
  - 1: Oppali
```



An oppali is a tenacious, twisting vine with white, trumpet-shaped flowers that grows in temperate and tropical regions. Stories passed down through generations refer to the oppali as a "bad luck vine" and warn against letting one take over a copse or garden, lest "your luck drain away like water down a hole." This folklore contains more wisdom than most farmers or settlers realize.

Oppalis are usually 30 feet long, but they twist and coil on themselves so much that they occupy a space not much larger than a horse.

### Oppali Trumpets

An oppali's tough trumpets are useful for creating thunderstones. Incorporating crushed oppali trumpet into crafting the thunderstone grants a +2 item bonus to the Crafting check, provided that this material makes up at least half of the raw materials used for the thunderstone. With a successful DC 27 Survival check check, a character harvests 5d20 gp of this raw material from a defeated oppali (double on a critical success, half on a failure, and none at all from a critical failure).
