---
title: "Crawling Slurry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uPAAs2VmggzC8ZqL" 
tags:
  - pf2e/creature/type/acid
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Crawling Slurry"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Crawling Slurry"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[acid]]
trait_02: [[mindless]]
trait_03: [[ooze]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +35, Stealth: +30"
abilityMods: [5, 9, 6, -5, 0, -5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +28, __Ref__ +31, __Will__ +20"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  acid,  critical hits,  poison,  precision,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Motion Sense"
    desc: "  A crawling slurry can sense nearby motion through vibration and air movement."

  - name: "Splatter"
    desc: "`pf2:r`  **Trigger** The crawling slurry takes bludgeoning damage from a creature it can sense within 10 feet\n* * *\n\n**Effect** The crawling slurry ejects a splash of acid onto the creature, dealing acid damage equal to the bludgeoning damage dealt to the crawling slurry (DC 37 Reflex check)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+32 ()\n__Damage__  3d10 + 11 bludgeoning plus grab 2d8 acid plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+3 bludgeoning damage plus 2d8 acid, DC 37 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crawling Slurry Acid"
    desc: "  A crawling slurry's acid damages metals and organic materials but not stone."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 37 Reflex check save, 5d10 acid damage, [[Actions/Escape|Escape]] DC 37, Rupture 20. A crawling slurry regains 30 healing Hit Points if a living creature it is engulfing dies.\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Crawling Slurry
creatures:
  - 1: Crawling Slurry
```



Acid damage can scar stone and reduce flesh to pitted chunks, but some organic compounds are resistant to acid and respond by combining into a mass of roiling, living slurry. These scarred clumps hunger to consume anything they can sense. They move with quick, darting contractions that surprise those used to facing slow-moving oozes.
