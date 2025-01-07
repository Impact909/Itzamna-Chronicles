---
title: "Mjolgat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.paoN05FDIBhxvnTU" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Mjolgat"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Mjolgat"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[beast]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Intimidation: +12, Survival: +10"
abilityMods: [5, 2, 4, -3, 2, -2]
speed: 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +8, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

  - name: "Orescent"
    desc: "  A mjolgat can detect the ores of unrefined precious metals with its powerful nose. Common earth and stone do not impede the mjolgat from smelling ores deep within the ground."

abilities_mid:
  - name: ""
  - name: "Head On"
    desc: "`pf2:r`  **Trigger** A creature the mjolgat can see targets the mjolgat with an attack\n* * *\n\n**Effect** The mjolgat swings its crest in the direction of the danger, gaining a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bone Crest"
    desc: "+10 ()\n__Damage__  2d10 + 7 bludgeoning"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+12 ()\n__Damage__  2d6 + 4 bludgeoning"

  - name: "Hammerhead"
    desc: "`pf2:2` (attack) The mjolgat rears upon its hind leg to crush an enemy with its jagged crest of bone. The mjolgat makes a bone crest Strike; on a hit, the mjolgat deals an extra die of damage. This counts as two attacks when calculating the mjolgat's multiple attack penalty"

  - name: "Punch-Drunk"
    desc: "  If the mjolgat critically fails a bone crest Strike, it becomes [[Conditions/Stunned|Stunned 1]] and [[Conditions/Stupefied|Stupefied 1]] for 1 round."

  - name: "Rockbreaker"
    desc: "  When the mjolgat deals damage to an object (such as a shield or an ore deposit), it deals double damage."

  - name: "Shrieking Slam"
    desc: "`pf2:2` (auditory,emotion,fear,mental) The mjolgat lets out a terrifying screech before bashing its head into the ground. Creatures within 30 feet of the mjolgat must attempt a DC 21 Will check save. Regardless of the result of the save, they are then immune to Shrieking Slam.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The target is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The target is [[Conditions/Frightened|Frightened 3]] and [[Conditions/Fleeing|Fleeing]] for 1 round."
 
```

```encounter-table
name: Mjolgat
creatures:
  - 1: Mjolgat
```




