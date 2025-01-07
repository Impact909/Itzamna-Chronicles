---
title: "Crawling Hand"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a3S8DYeNYxneaJ3D" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Crawling Hand"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Crawling Hand"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Lifesense 30 Feet, Tremorsense (Imprecise) 30 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +5, Stealth: +6, Survival: +2"
abilityMods: [1, 3, 0, -4, 0, 0]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +2, __Ref__ +5, __Will__ +2"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  visual,  bleed"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+7 (agile, finesse)\n__Damage__  1d4 + 1 slashing plus grab"

  - name: "Mark Quarry"
    desc: "  A crawling hand can be assigned a quarry by anointing the hand with a drop of the intended quarry's blood. If the hand ever has no quarry, it automatically gains the next creature it damages as its quarry. The hand gains a +1 circumstance bonus to Perception checks when it [[Actions/Seek|Seeks]] its quarry, to Survival checks when it [[Actions/Track|Tracks]] its quarry, and damage rolls when it Strikes its quarry."

  - name: "Throat Grab"
    desc: "`pf2:1`  This ability functions as Grab, but the crawling hand grips the throat of a Medium or smaller creature. A creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] this way has difficulty speaking and must spend an extra action to perform any action that requires speaking, including casting spells.\n* * *\n\n**Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Crawling Hand
creatures:
  - 1: Crawling Hand
```



A crawling hand formed from the appendage of a Medium creature is quick and agile, skittering in the shadows until it can strike its prey.

* * *

Typically, crawling hands form when severed appendages are endowed with a crude sentience by necromantic energies that turn them into tireless killers. Yet, crawling hands can also arise spontaneously, usually when a creature loses an appendage in a place rife with necromantic energy or with a connection to the Void.
