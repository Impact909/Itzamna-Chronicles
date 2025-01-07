---
title: "Gurlunk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ODNRlm4LjVgyYpMs" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/goblin
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Gurlunk"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Gurlunk"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[goblin]]
trait_04: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Intimidation: +8, Nature: +9, Stealth: +10, Survival: +9"
abilityMods: [2, 4, 2, 0, 3, 0]
speed: 25 feet
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +12, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dogslicer|Dogslicer]], [[Equipment/Composite Shortbow|+1 Composite Shortbow]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Actor.iaddEHUH7gLx2WNr.Item.czwGWW73rkPW7vBg|Goblin Scuttle]]"
    desc: "`pf2:r`  **Trigger** A goblin ally ends a move action adjacent to the goblin.\n* * *\n\n**Effect** The goblin [[Actions/Step|Steps]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dogslicer"
    desc: "+12 (agile, backstabber, finesse, goblin)\n__Damage__  1d6 + 2 slashing"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+13 (deadly d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  1d6 + 6 piercing"

  - name: "Disorienting Shot"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Gurlunk makes two Strikes against his hunted prey with his shortbow. If both hit the same creature, the creature succeed at a DC 21 Will check save or become [[Conditions/Off-Guard|Off-Guard]] until the start of their next turn (or the start of Gurlunk's next turn on a critical failure)."

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) Gurlunk designates a single creature he can see or hear, and gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] and [[Actions/Track|Track]] that prey. He can only have one creature so designated at a time, and if he selects a new hunted prey, the previous designation ends."

  - name: "Hunter's Edge"
    desc: "  Gurlunk deals an additional 1d8 precision damage the first time he hits his hunted prey in a round."

  - name: "Whistling Threat"
    desc: "`pf2:2` (concentrate,emotion,fear,mental,primal) **Frequency** once per day\n* * *\n\n**Effect** Gurlunk whistles sharply at a Medium or larger animal or beast he can see within 30 feet, using his voice to dull the creature's wits and cause it to lower its defenses. The target must attempt a DC 21 Will check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The target is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The target is [[Conditions/Frightened|Frightened 3]] and [[Conditions/Slowed|Slowed 1]] for 1 round as it shakes in fear."
 
```

```encounter-table
name: Gurlunk
creatures:
  - 1: Gurlunk
```


Male goblin ranger


