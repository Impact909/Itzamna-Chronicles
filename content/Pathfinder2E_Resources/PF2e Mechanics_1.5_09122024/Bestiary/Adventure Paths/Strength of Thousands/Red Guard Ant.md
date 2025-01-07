---
title: "Red Guard Ant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MfKStC93qnsTFKWa" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Red Guard Ant"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Red Guard Ant"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Intimidation: +27, Survival: +27"
abilityMods: [8, 4, 6, -2, 6, 4]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +29, __Ref__ +23, __Will__ +26"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Stinger Only)]]"
    desc: "`pf2:r`  Stinger only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+30 ()\n__Damage__  3d10 + 14 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+30 (agile)\n__Damage__  3d6 + 14 piercing plus red-ant-venom"

  - name: "Formic Acid Spray"
    desc: "`pf2:2` (acid,primal) The red guard ant sprays a 15-foot cone of acid from its abdomen that deals 10d10 acid damage (DC 34 Reflex check). It can't use Formic Acid Spray again for 1d4 rounds."

  - name: "Haul Away"
    desc: "`pf2:1`  **Requirements** The red guard ant has a Huge or smaller creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The ant Strides up to its full Speed, carrying the grabbed creature with it. It's encumbered if the grabbed creature is Large or larger."

  - name: "Pack Attack"
    desc: "  A red guard ant deals an additional 2d6 precision damage to any creature within reach of at least two of the ant's allies."

  - name: "Red Ant Venom"
    desc: " (poison) **Saving Throw** DC 36 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "Swarming Flank"
    desc: "  If at least three red guard ants have a creature within their reach, they flank the creature, even if they can't draw a line to each other that passes through opposite sides of the creature's space."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Red Guard Ant
creatures:
  - 1: Red Guard Ant
```




