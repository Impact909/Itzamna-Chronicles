---
title: "Living Tar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.X7uC3ts43gkEHAOy" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Living Tar"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Living Tar"
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
sourcebook: "_Pathfinder Monster Core_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +18, __Ref__ +6, __Will__ +11"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165; __Immunities__  acid,  bleed,  bludgeoning,  critical hits,  mental,  precision,  unconscious,  visual"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A living tar can feel nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Adhesive Mass"
    desc: "  A weapon that hits the living tar is stuck to the ooze. Removing it requires a successful DC 23 Athletics check check to Break Open. The living tar can have any number of objects or creatures stuck to it at a time.\n\nIt can release a stuck object with an Interact action, and the adhesive dissolves 1 minute after the ooze dies, releasing all stuck objects and creatures."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+18 (reach 10 feet)\n__Damage__  2d6 acid plus grab 2d8 + 7 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+7 bludgeoning + 1d6 acid, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 22 Reflex check, 4d6 acid damage, [[/act escape dc=22]], Rupture 15\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Living Tar
creatures:
  - 1: Living Tar
```



Most often found belowground, these oozes scour caves for objects to dissolve with their corrosive secretions. These sticky masses are often filled with bones, fossils, and discarded weaponry from adventurers.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
