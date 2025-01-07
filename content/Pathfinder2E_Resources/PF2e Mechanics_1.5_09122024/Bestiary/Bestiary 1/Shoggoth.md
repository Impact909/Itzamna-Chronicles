---
title: "Shoggoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cxXE7Uq67aUetSKM" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Shoggoth"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Shoggoth"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[amphibious]]
trait_03: [[chaotic]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 60 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +36, Intimidation: +29"
abilityMods: [10, 6, 9, -3, 6, 1]
speed: 40 feet,  climb 25 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 39
armorclass:
  - name: AC
    desc: "39 all-around vision; __Fort__ +33, __Ref__ +30, __Will__ +30; +1 status to all saves vs. magic"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275, fast healing 20; __Immunities__  blinded,  controlled,  critical hits,  deafened,  precision,  sleep; __Resistances__ acid 20, cold 20, sonic 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 20]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Maddening Cacophony"
    desc: " (auditory,aura,incapacitation,mental) 60 feet. A shoggoth constantly voices syllables and mutterings that mortals were not meant to hear. A creature entering the aura or starting its turn in the aura must succeed at a DC 38 Will check save or become confused for 1 round (2d4 rounds on a critical failure). A creature that successfully saves is temporarily immune for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+35 (magical, reach 30 feet)\n__Damage__  4d10 + 18 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+15 bludgeoning, DC 40 Fortitude check\n* * *\n\n_Note: A DC was not provided for this ability by Paizo. The DC present here is a moderate DC for the creature level according to the Gamemastery Guide creature building Tables._\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Eat Away"
    desc: "  A creature that begins its turn inside the shoggoth takes 9d6 acid damage."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 40 Reflex check, 6d6 acid damage, Escape DC 40, Rupture 40\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shoggoth
creatures:
  - 1: Shoggoth
```



Although even raving fanatics and doom-saying prophets desperately claim the monstrous shoggoth is nothing more than a drug-induced vision or a thankfully unreal nightmare, the truth is altogether more dire. Shoggoths exist, yet they tend keep to the deepest of ocean trenches or the most remote of caverns and ruins, emerging to spread chaos and destruction in their slimy wakes.

The first shoggoths were created by an alien species to serve as mindless beasts of burden. Their vast bulk, incredible strength, and amorphous nature made them useful slave labor, and their ability to spontaneously form whatever new eyes, mouths, limbs, and other organs they might need made them incredibly versatile. Eventually, the shoggoths developed enough intelligence to rebel against their masters, and now they lurk, patient but potent, in the lightless deeps.

A shoggoth has goals and methods unknowable to humanoid beings. They remember their eons of servitude and, compared to their mysterious masters, humans, elves, dwarves and other intelligent beings are mere specks which crawl upon the surface of the world, indistinguishable from animals. When a shoggoth rolls its immense, hideous body over a band of explorers, engulfing them in a gelatinous press of flesh and gnawing teeth, it is not so much evil as uncaring.

Shoggoths can become the object of worship for humanoid cults dedicated to chaos and entropy. The shoggoth does not respond to this worship, but it can be counted on to consume any hapless victim the cult can capture and sacrifice to it. Rumors of shoggoths that have developed even greater intellects are, one would hope, just that, for the damage a shoggoth capable of reasoning could wreak upon a world is unsettling to say the least.
