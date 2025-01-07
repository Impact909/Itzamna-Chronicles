---
title: "Kilia Mwibo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cVbdk8XuHJzRkmy9" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Kilia Mwibo"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Kilia Mwibo"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[plant]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; "
languages: "Fey; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Deception: +25, Stealth: +28"
abilityMods: [7, 5, 3, -2, 5, 0]
speed: 25 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +29, __Will__ +26"
hp: 345
health:
  - name: ""
  - name: HP
    desc: "345; __Immunities__  critical hits,  precision; __Weaknesses__ fire 15, slashing 15; __Resistances__ sonic 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Frond Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Despairing Presence"
    desc: " (aura,emotion,fear,incapacitation,mental,primal) 60 feet. A creature that enters the emanation or starts its turn within it tumbles down a deep well of dread and must attempt a DC 33 Will check save.\n\n**Critical Success** The target is unaffected.\n\n**Success** The target becomes [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The target becomes [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The target becomes [[Conditions/Frightened|Frightened 3]] and [[Conditions/Immobilized|Immobilized]] until it's no longer frightened."

  - name: "Emotion Sense 60 feet"
    desc: "  A kilia mwibo can sense nearby negative emotions. This is a precise sense against creatures who are under powerful emotion effects like rage, those who are frightened, or, at the GM's discretion, those who are in the grips of hatred, sadness, or other overwhelming negative emotions. Against all other creatures that possess emotions, this is an imprecise sense. A creature that has no emotions is effectively [[Conditions/Invisible|Invisible]] to a kilia mwibo. A creature that knows about emotion sense can take precautions to Hide and Sneak from a kilia mwibo, in this case by suppressing feelings of negativity."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Frond"
    desc: "+30 (deadly d12, reach 15 feet, sweep, versatile p)\n__Damage__  3d10 + 15 slashing plus improved-grab 1d6 bleed plus improved-grab"

  - name: "**Melee** `pf2:1` Root"
    desc: "+28 (reach 20 feet, sweep, trip)\n__Damage__  3d8 + 15 bludgeoning"

  - name: "**Ranged** `pf2:1` Thorn"
    desc: "+28 (deadly d12, range increment 60 feet)\n__Damage__  3d6 + 15 piercing"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d12+15 bludgeoning, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Consume Emotion"
    desc: "`pf2:2` (divine,mental) The kilia mwibo feeds on the negative emotions of a creature within 60 feet; this must be a creature that it can precisely sense with its emotion sense. The target must succeed at a DC 36 Will check save or increase its [[Conditions/Drained|Drained]] condition value by 1 (by 2 on a critical failure), to a maximum of drained 4."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Kilia Mwibo
creatures:
  - 1: Kilia Mwibo
```




