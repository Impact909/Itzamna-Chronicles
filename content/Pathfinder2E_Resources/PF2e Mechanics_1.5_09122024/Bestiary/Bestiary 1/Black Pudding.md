---
title: "Black Pudding"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.N1eMqRPWM7M8MmZl" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Black Pudding"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Black Pudding"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18"
abilityMods: [7, -5, 7, -5, 0, -5]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +18, __Ref__ +6, __Will__ +11"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165; __Immunities__  acid,  critical hits,  piercing,  precision,  slashing,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A black pudding can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Corrosive Mass"
    desc: "  A creature that hits the pudding with a metal or wooden weapon must succeed at a DC 22 Reflex check save or the weapon takes 2d6 acid damage (after dealing damage to the black pudding as normal). Thrown weapons and ammunition take this damage automatically with no save."

  - name: "Split"
    desc: "  When the black pudding is hit by an attack that would deal slashing or piercing damage and has 10 or more HP, it splits into two identical puddings, each with half the original's HP.\n\nOne pudding is in the same space as the original, and the other appears in an adjacent unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or sturdy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+18 (reach 10 feet)\n__Damage__  2d8 + 7 bludgeoning plus corrosive-touch,grab 2d6 acid plus corrosive-touch,grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+7 bludgeoning damage plus 1d6 acid damage, DC 26 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Corrosive Touch"
    desc: "  When the pudding hits a creature with its pseudopod, any acid damage is dealt to the creature's armor or clothing as well as the creature."

  - name: "Suction"
    desc: "  The pudding can climb on ceilings and other inverted surfaces, though such surfaces are difficult terrain for it."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Black Pudding
creatures:
  - 1: Black Pudding
```



Most often found below ground, these oozes scour caves for objects to dissolve with their corrosive secretions. This caustic acid is particularly dangerous to creatures that attack a pudding, as it can quickly damage and destroy gear.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
