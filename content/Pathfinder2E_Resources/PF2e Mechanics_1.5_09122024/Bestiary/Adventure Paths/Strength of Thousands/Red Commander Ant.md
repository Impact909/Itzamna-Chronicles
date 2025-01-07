---
title: "Red Commander Ant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LXkJjeaKwf8fMH6U" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Red Commander Ant"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Red Commander Ant"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Diplomacy: +32, Intimidation: +32, Nature: +29, Survival: +29"
abilityMods: [9, 5, 6, 0, 6, 9]
speed: 40 feet,  climb 20 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +29, __Ref__ +28, __Will__ +31"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+33 (reach 10 feet)\n__Damage__  3d10 + 17 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+33 (agile, reach 10 feet)\n__Damage__  3d6 + 17 piercing plus red-ant-venom"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  5d10 bludgeoning damage, DC 38 Fortitude check.\n\nBefore using Constrict, the ant can choose to smash one creature that it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] against the ground. That creature uses the result one degree of success worse than its Fortitude save result against Constrict, but it is then no longer Grabbed or restrained by the ant.\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "For the Queen!"
    desc: "`pf2:2` (olfactory) The red commander ant gives a pheromone signal to spur other ants into a fury. All ants within 30 feet who can smell this signal gain a +1 status bonus to attack rolls, reduce their frightened condition to 0, and are immune to the frightened condition for 1 minute."

  - name: "Red Ant Venom"
    desc: " (poison) **Saving Throw** DC 38 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "The Queen's Enemy"
    desc: "`pf2:1` (concentrate) The red commander ant designates a single creature within 60 feet that it can see as its queen's enemy. All ants within 120 feet of the red commander ant deal an additional 1d8 bleed damage when they hit the target with mandibles Strikes. These effects last for 1 minute, or until the red commander ant uses The Queen's Enemy on a different creature."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Red Commander Ant
creatures:
  - 1: Red Commander Ant
```




