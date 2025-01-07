---
title: "Ochre Jelly"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.O16cVfDyLidvM0tm" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Ochre Jelly"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Ochre Jelly"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13"
abilityMods: [4, -5, 6, -5, 0, -5]
speed: 15 feet,  climb 10 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +15, __Ref__ +4, __Will__ +7"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  acid,  critical hits,  electricity,  piercing,  precision,  slashing,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A ochre jelly can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Split"
    desc: "  Whenever an ochre jelly is hit by an attack or effect that would deal slashing, piercing, or electricity damage and the ochre jelly has at least 10 HP, the jelly splits into two identical jellies with half the original's HP.\n\nOne jelly is in the same space as the original, and the other appears in an adjacent unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or sturdy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+15 ()\n__Damage__  1d8 + 7 bludgeoning plus grab 2d4 acid plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+3 bludgeoning damage plus 2d4 acid damage, DC 23 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Ochre Acid"
    desc: "  An ochre jelly's acid damages only flesh-not bone, stone, wood, or other materials."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ochre Jelly
creatures:
  - 1: Ochre Jelly
```



Ochre jellies are animate masses of protoplasm with a sickly combination of yellow, orange, and brown hues. Their acidic bodies dissolve flesh but leave other materials, including a victim's gear and bones, intact. Some ancient cultures would entomb bodies in stone sarcophaguses with ochre jellies to allow the ooze to break down the flesh and clean and polish the bones.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
