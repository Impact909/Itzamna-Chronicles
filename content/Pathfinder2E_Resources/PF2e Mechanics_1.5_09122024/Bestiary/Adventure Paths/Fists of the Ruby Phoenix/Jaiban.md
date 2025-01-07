---
title: "Jaiban"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.h7DsgjYpen3tKbRi" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Jaiban"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Jaiban"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30, Stealth: +28, Survival: +26"
abilityMods: [9, 4, 8, -4, 3, 1]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +23, __Will__ +25"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+31 (reach 20 feet)\n__Damage__  3d12 + 14 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+31 (reach 25 feet)\n__Damage__  3d6 + 14 bludgeoning"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+31 (reach 15 feet)\n__Damage__  3d8 + 14 bludgeoning"

  - name: "Quaking Stomp"
    desc: "`pf2:1` (manipulate) **Frequency** once per minute\n* * *\n\n**Effect** Jaiban stomps the ground with intense force. It creates a minor earthquake with the effects of the [[Spells/Earthquake|Earthquake]] spell, except that the range is only 100 feet and is contained to a 20-foot burst."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 36 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Whip Tail"
    desc: "`pf2:2` (sonic) Jaiban cracks its tail, creating a sonic boom in a 5-foot burst centered on a corner within reach of its tail Strike. Each creature in the burst's area must attempt a DC 36 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 2]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 3]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Jaiban
creatures:
  - 1: Jaiban
```


Legendary beast of Bonmu


