---
title: "Giant Crawling Hand"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0dpUkofpLENdyQ4Q" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Giant Crawling Hand"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Crawling Hand"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Lifesense 30 Feet, Tremorsense (Imprecise) 30 Feet"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +11, Survival: +12"
abilityMods: [4, 2, 4, -4, 3, 0]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +13, __Ref__ +11, __Will__ +10"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  visual,  bleed"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Pus Burst"
    desc: "`pf2:r`  **Trigger** The giant crawling hand takes piercing or slashing damage\n* * *\n\n**Effect** A random creature adjacent to the giant crawling hand is sprayed with vile pus that deals 4d6 void damage. The affected creature must attempt a DC 21 Reflex check save.\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes half damage and becomes [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes full damage and becomes [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature takes double damage and becomes [[Conditions/Sickened|Sickened 3]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 ()\n__Damage__  2d6 + 7 slashing plus grab"

  - name: "Mark Quarry"
    desc: "  A crawling hand can be assigned a quarry by anointing the hand with a drop of the intended quarry's blood. If the hand ever has no quarry, it automatically gains the next creature it damages as its quarry. The hand gains a +1 circumstance bonus to Perception checks when it [[Actions/Seek|Seeks]] its quarry, to Survival checks when it [[Actions/Track|Tracks]] its quarry, and damage rolls when it Strikes its quarry."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Crawling Hand
creatures:
  - 1: Giant Crawling Hand
```



A giant crawling hand is the appendage of a very large creature, such as a giant.

* * *

Typically, crawling hands are formed when severed appendages are endowed with a crude sentience by evil necromantic energies that turn them into tireless killers. Yet crawling hands can also arise spontaneously, usually when a creature loses an appendage in a place rife with necromantic energy or with a connection to the Void.
