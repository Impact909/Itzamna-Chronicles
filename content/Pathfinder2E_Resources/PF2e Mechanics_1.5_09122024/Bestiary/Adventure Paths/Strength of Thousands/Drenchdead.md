---
title: "Drenchdead"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M63QF67ood56rnW3" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Drenchdead"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Drenchdead"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[water]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Wavesense (Precise) 60 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +25, Stealth: +23, Survival: +19"
abilityMods: [7, 3, 4, 0, 1, 3]
speed: 20 feet,  swim 35 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +24, __Ref__ +21, __Will__ +19"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (precise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile)\n__Damage__  3d6 + 13 slashing plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+26 ()\n__Damage__  3d10 + 13 piercing"

  - name: "Aquatic Camouflage"
    desc: "  When fully submerged in water, the drenchdead can Hide from other creatures even if it doesn't have cover against them and isn't [[Conditions/Concealed|Concealed]] from them."

  - name: "Drag Down"
    desc: "`pf2:2`  **Requirements** The drenchdead is swimming in water at least 10 feet deep\n* * *\n\n**Effect** The drenchdead attempts an Athletics check to [[Actions/Grapple|Grapple]] an adjacent creature (on nearby land or in the water). On a success against a creature on land, in addition to the normal effects of Grapple, the drenchdead pulls the creature into the water into a space adjacent to itself. If the creature is already in the water, on a success, in addition the normal effects of Grapple, the drenchdead drags the creature 10 feet deeper, moving 10 feet with the creature. Moving a creature into water or deeper into water using Drag Down is forced movement for the target creature, but not for the drenchdead."

  - name: "Drowning Touch"
    desc: "`pf2:2` (incapacitation,occult,water) The drenchdead touches a creature and causes water from its own body to flow into the creature's lungs. If the creature can't breathe water, it must attempt a DC 32 Fortitude check save.\n\n**Success** The creature is unaffected and is temporarily immune to Drowning Touch for 24 hours.\n\n**Failure** The creature becomes [[Conditions/Sickened|Sickened 3]].\n\n**Critical Failure** The creature chokes on the water and runs out of air. It falls [[Conditions/Unconscious|Unconscious]] and starts drowning. If the creature is above water, it recovers from drowning as soon as it succeeds at a saving throw against suffocation."

  - name: "Surface Skimmer"
    desc: "  A drenchdead submerged in water has cover from attacks made by creatures out of the water."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Drenchdead
creatures:
  - 1: Drenchdead
```




