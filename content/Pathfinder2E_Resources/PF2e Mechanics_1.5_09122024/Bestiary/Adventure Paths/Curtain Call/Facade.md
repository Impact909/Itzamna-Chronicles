---
title: "Facade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.c8RS6zCKNY4akYJx" 
tags:
  - pf2e/creature/type/astral
  - pf2e/creature/type/construct
  - pf2e/creature/type/eidolon
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Facade"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Facade"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[astral]]
trait_02: [[construct]]
trait_03: [[eidolon]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Arcana: +21, Crafting: +21"
abilityMods: [6, 3, 5, 2, 0, -1]
speed: 25 feet
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +28, __Ref__ +26, __Will__ +23; +2 vs. death effects, disease, poison, and effects causing the fatigued or sickened conditions"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Heart"
    desc: "  Facade removes persistent bleed damage on a DC 10 flat check (DC 5 with aid)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (agile, magical, shove)\n__Damage__  3d10 + 14 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+14 bludgeoning, DC 38 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Encase in Wax"
    desc: "`pf2:1`  **Requirements** Facade's previous action was to Constrict a creature\n* * *\n\n**Effect** Facade encases the creature they just Constricted with wax. That creature becomes [[Conditions/Slowed|Slowed 1]] until it takes a 3-action activity to Interact with the wax and peel it off."

  - name: "Remake Self"
    desc: "`pf2:1` (arcane,polymorph) Facade changes their appearance to be similar to any Medium humanoid creature they've seen, though they're still obviously a wax statue and can't use this ability to [[Actions/Impersonate|Impersonate]] that creature."

  - name: "Unsettle"
    desc: "`pf2:r` (arcane,emotion,fear,mental) **Trigger** Facade Strikes a creature they've assumed the basic appearance of\n* * *\n\n**Effect** s The damaged creature becomes [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical hit)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Facade
creatures:
  - 1: Facade
```




