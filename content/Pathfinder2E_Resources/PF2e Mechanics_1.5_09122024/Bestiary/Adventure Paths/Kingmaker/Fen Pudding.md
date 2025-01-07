---
title: "Fen Pudding"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WNQgOP3D0kECWRYr" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Fen Pudding"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Fen Pudding"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[mindless]]
trait_03: [[ooze]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +26, Stealth: +23"
abilityMods: [7, -5, 7, -5, 0, -5]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +26, __Ref__ +11, __Will__ +16"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  acid,  critical hits,  piercing,  precision,  slashing,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A fen pudding can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Corrosive Mass"
    desc: "  A creature that hits the pudding with a metal or wooden weapon must succeed at a DC 29 Reflex check save or the weapon takes 2d6 acid damage (after dealing damage to the fen pudding as normal). Thrown weapons and ammunition take this damage automatically with no save."

  - name: "Split"
    desc: "  When the fen pudding is hit by an attack that would deal slashing or piercing damage and has 10 or more HP, it splits into two identical puddings, each with half the original's HP.\n\nOne pudding is in the same space as the original, and the other appears in an adjacent unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or sturdy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+26 (reach 10 feet)\n__Damage__  2d8 + 12 bludgeoning plus corrosive-touch,grab 2d8 acid plus corrosive-touch,grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+12 bludgeoning damage plus 1d6 acid damage, DC 32 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Corrosive Touch"
    desc: "  When the pudding hits a creature with its pseudopod, any acid damage is dealt to the creature's armor or clothing as well as the creature."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Fen Pudding
creatures:
  - 1: Fen Pudding
```


Variant black pudding

Most often found below ground, these oozes scour caves for objects to dissolve with their corrosive secretions. This caustic acid is particularly dangerous to creatures that attack a pudding, as it can quickly damage and destroy gear.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
