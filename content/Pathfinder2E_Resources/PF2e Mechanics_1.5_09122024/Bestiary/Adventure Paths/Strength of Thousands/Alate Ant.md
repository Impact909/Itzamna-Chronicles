---
title: "Alate Ant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cMp2cOeT575uiLvo" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Alate Ant"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Alate Ant"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Intimidation: +28, Survival: +28"
abilityMods: [4, 8, 6, -1, 6, 4]
speed: 40 feet,  climb 20 feet,  fly 40 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +24, __Ref__ +30, __Will__ +28"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Darting Flight"
    desc: "`pf2:r`  **Requirements** The alate ant is flying\n\n**Trigger** The ant is targeted with an attack by an attacker it can see\n* * *\n\n**Effect** The ant gains a +2 circumstance bonus to AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+32 (finesse)\n__Damage__  3d8 + 10 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+32 (agile, finesse)\n__Damage__  3d4 + 10 piercing plus red-ant-venom"

  - name: "Frenzy"
    desc: "`pf2:1`  **Frequency** Once per day\n* * *\n\n**Effect** The alate ant enters a state of jittery agitation. It becomes [[Conditions/Quickened|Quickened]] for 3 rounds and can use the extra action only to Fly or Strike."

  - name: "Pack Attack"
    desc: "  The alate ant deals an additional 3d6 precision damage to any creature within reach of at least two of the ant's allies."

  - name: "Pheromone Spray"
    desc: "`pf2:2` (emotion,mental) The alate ant sprays a cloud of pheromones in a 15-foot cone. Non-ant creatures in the cone must succeed at a DC 37 Will check save or become [[Conditions/Confused|Confused]] for 1d4 rounds (1 minute on a critical failure). It can't use Pheromone Spray again for 1d4 rounds."

  - name: "Red Ant Venom"
    desc: " (poison) While a creature is enfeebled from this poison, it is [[Conditions/Confused|Confused]] (this confusion is an emotion, enchantment, and mental effect).\n\n**Saving Throw** DC 37 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Alate Ant
creatures:
  - 1: Alate Ant
```




