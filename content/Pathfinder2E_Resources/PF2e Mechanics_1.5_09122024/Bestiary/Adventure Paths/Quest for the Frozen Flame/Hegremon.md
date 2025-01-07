---
title: "Hegremon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.f9Af8wIjCPvaemDB" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Hegremon"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Hegremon"
level: "Creature 13"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[evil]]
trait_04: [[giant]]
trait_05: [[humanoid]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Low-Light Vision"
languages: "Common, Hallit, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +25, Crafting: +24, Intimidation: +23, Medicine: +23, Nature: +27, Stealth: +27, Survival: +27"
abilityMods: [6, 8, 4, 5, 6, 4]
speed: 30 feet,  climb 15 feet
sourcebook: "_Pathfinder #177: Burning Tundra_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +23, __Ref__ +27, __Will__ +21"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  cold; __Weaknesses__ fire 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Mammoth Bow|Mammoth Bow]], 2x [[Equipment/Shortsword|+1 Striking Shortsword]], [[Equipment/Chain Shirt|Chain Shirt]], 30x [[Equipment/Arrows|Arrows]], [[Equipment/Potion of Fire Resistance (Moderate)|Potion of Fire Resistance (Moderate)]]"
abilities_mid:
  - name: ""
  - name: "Evasion"
    desc: "  When Hegremon rolls a success on a Reflex save, he gets a critical success instead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+26 (agile, finesse, magical, reach 10 feet, versatile p)\n__Damage__  2d6 + 12 slashing"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+25 (agile, finesse, reach 10 feet)\n__Damage__  3d6 + 12 bludgeoning"

  - name: "**Ranged** `pf2:1` Mammoth Bow"
    desc: "+27 (deadly d10, magical, propulsive, range increment 180 feet, reload 0, volley 50 ft.)\n__Damage__  3d8 + 9 piercing 2d6 piercing"

  - name: "Aimed Shot"
    desc: "`pf2:2` (concentrate) Hegremon makes a single _mammoth bow_ Strike against his prey; he gains a +2 circumstance bonus to the attack roll and ignores his prey's [[Conditions/Concealed|Concealed]] condition."

  - name: "Chill Breath"
    desc: "`pf2:1`  (cold, evocation, primal) Hegremon breathes out a 15-foot cone of freezing moisture that quickly condenses into ice, dealing 6d6 cold damage. Each creature in the cone must attempt a DC 28 Reflex check. A creature that fails its save is also [[Conditions/Immobilized|Immobilized]] and takes 2d6 cold damage at the end of each of its turns until it breaks free (Escape DC 28). Hegremon can't use Chill Breath again for 1d4 rounds."

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) Hegremon designates a single creature he can see and hear, or one he's Tracking, as his prey. Hegremon has a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] his prey and a +2 circumstance bonus to Survival checks to [[Actions/Track|Track]] his prey. He ignores the penalty to ranged attacks within his second range increment against his prey. The first time Hegremon hits his prey in a round, he inflicts an additional 2d8 precision damage. These effects last until Hegremon uses Hunt Prey again."

  - name: "Hunting Shot"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** Hegremon makes two _mammoth bow_ Strikes against his prey. If both hit, combine their damage for the purposes of resistances and weaknesses. His multiple attack penalty applies to each Strike normally."

  - name: "Ice Stride"
    desc: "  Hegremon isn't impeded by difficult terrain caused by snow or ice, nor does he need to attempt Acrobatics checks to keep from falling on slippery ice."

  - name: "Nature's Edge"
    desc: "  Creatures in natural difficult terrain or on natural uneven ground are [[Conditions/Off-Guard|Off-Guard]] to Hegremon."

  - name: "Penetrating Shot"
    desc: "`pf2:2`  Hegremon chooses a target that's giving lesser cover to his prey and makes a _mammoth bow_ Strike against the chosen target and his prey. This attack ignores lesser cover the chosen target provides his prey. Hegremon rolls damage twice and applies it to each creature he hits. A Penetrating Shot counts as two attacks for his multiple attack penalty."
 
```

```encounter-table
name: Hegremon
creatures:
  - 1: Hegremon
```




