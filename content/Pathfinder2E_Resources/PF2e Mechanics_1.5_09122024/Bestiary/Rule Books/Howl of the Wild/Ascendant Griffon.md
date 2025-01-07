---
title: "Ascendant Griffon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hXuZe0IVSqdTCwTg" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Ascendant Griffon"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Ascendant Griffon"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Scent (Imprecise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +23, Intimidation: +25, Stealth: +21, Survival: +22"
abilityMods: [7, 6, 5, -4, 3, 7]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +21, __Ref__ +24, __Will__ +18"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Dread Gaze"
    desc: "`pf2:r`  **Trigger** A creature ends a move action within 30 feet of the ascendant griffon\n* * *\n\n**Effect** The ascendant griffon turns its head to stare down the triggering creature, and attempts to [[Actions/Demoralize|Demoralize]] it. This use of Demoralize has the visual trait rather than the auditory trait, and the griffon does not take a penalty on its check for not sharing a language."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+24 ()\n__Damage__  4d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+24 (agile)\n__Damage__  4d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+24 ()\n__Damage__  4d6 + 10 piercing plus improved-grab"

  - name: "**Ranged** `pf2:1` Feather"
    desc: "+25 (range 60 feet)\n__Damage__  2d8 + 10 piercing"

  - name: "Carry Off"
    desc: "  An ascendant griffon can Fly at full speed with a creature [[Conditions/Grabbed|Grabbed]] in its talons, moving that creature along with it."

  - name: "Disembowel"
    desc: "`pf2:1`  **Requirements** The ascendant griffon has a creature [[Conditions/Grabbed|Grabbed]] in its talons\n* * *\n\n**Effect** The griffon makes a beak Strike to rip at the flesh of its prey. If the Strike hits, that creature becomes [[Conditions/Drained|Drained 1]] (or increases its drained value by 1, to a maximum of 4)."

  - name: "Razor-Edged Flight"
    desc: "`pf2:2`  The ascendant griffon glides violently forward, Flying twice. It makes a wing Strike at any point during the movement against up to two different targets; if either of these attacks is a critical hit, the target also takes 2d6 persistent bleed damage."

  - name: "Terrifying Screech"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The ascendant griffon unleashes a fearsome cry that strikes terror into its prey. Each creature within 100 feet must attempt a DC 30 Will check save. Regardless of the result, creatures are temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is frightened 2 and [[Conditions/Fleeing|Fleeing]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ascendant Griffon
creatures:
  - 1: Ascendant Griffon
```




