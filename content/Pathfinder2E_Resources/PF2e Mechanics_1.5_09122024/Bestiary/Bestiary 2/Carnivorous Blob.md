---
title: "Carnivorous Blob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.drNrRa1DAydkqMP0" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Carnivorous Blob"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Carnivorous Blob"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Motion Sense (Precise) 240 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27"
abilityMods: [8, -3, 6, -5, 0, -5]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +25, __Ref__ +14, __Will__ +19"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  acid,  critical hits,  piercing,  precision,  slashing,  sonic,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A carnivorous blob can sense nearby creatures through vibration and air or water movement."

abilities_mid:
  - name: ""
  - name: "Reactive Strikes"
    desc: "`pf2:r`  **Trigger** The carnivorous blob takes damage from any source\n* * *\n\n**Effect** The blob makes a pseudopod Strike against an adjacent target. If an adjacent creature dealt the triggering damage, that creature is the target of this Reactive Strike."

  - name: "Split"
    desc: "  When a carniverous blob that has 10 or more HP is hit by an attack that would deal piercing or slashing damage, it splits into two identical oozes, each with half the original's HP. One ooze is in the same space as the original, and the other is in an adjacent, unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or heavy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+26 (reach 30 feet)\n__Damage__  2d12 + 12 bludgeoning plus grab 2d6 acid plus grab"

  - name: "Carnivorous Blob Acid"
    desc: "  A carnivorous blob's acid damages only flesh-not bone, stone, wood, or other materials- but is nonetheless devastating. Whenever a creature takes damage from this acid, it must succeed at a DC 33 Fortitude check save or become [[Conditions/Drained|Drained 1]] (drained 2 on a critical failure). On each subsequent failure, the drained condition value increases by 1 (or by 2 on a critical failure), to a maximum of drained 4."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d12 bludgeoning plus 2d6 acid, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 33, 4d10 acid damage, Escape DC 33, Rupture 20\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Carnivorous Blob
creatures:
  - 1: Carnivorous Blob
```



Carnivorous blobs are the ravenous spawn of shattered worlds far beyond the stars, born across the galaxy in inert form until they fall like meteorites onto unsuspecting worlds. These massive beings can lie dormant for years in desolate caverns or barren wastelands. When a carnivorous blob perceives living creatures nearby, it lurches to gelatinous life, seeking out and consuming every creature it can catch until it is destroyed or until it has been unable to locate food for 24 hours, at which point it returns to hibernation. Often, keeping food away from a carnivorous blob is the safest way to defeat it. The blob's ability to split into smaller oozes that might stay hidden after a fight means it can be hard to fully eradicate these mindless predators.
