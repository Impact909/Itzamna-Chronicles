---
title: "Headless Rustler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DS8gUvZA569jLBSN" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Headless Rustler"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Headless Rustler"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Lifesense 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Intimidation: +17, Stealth: +13, Survival: +15"
abilityMods: [6, 2, 2, 2, 3, 4]
speed: 20 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +13, __Ref__ +15, __Will__ +17"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95, fast healing 5; __Immunities__  death effects,  disease,  fear effects,  paralyzed,  poison,  unconscious; __Weaknesses__ holy 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+1 Longsword]], [[Equipment/Arquebus|+1 Arquebus]], [[Equipment/Full Plate|Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 5]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet. DC 23 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Keen Longsword"
    desc: "+18 (magical, versatile p)\n__Damage__  1d8 + 10 slashing plus head-hunter"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, nonlethal)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Keen Striking Arquebus"
    desc: "+18 (concussive, fatal d12, kickback, magical, range increment 150 feet)\n__Damage__  2d8 + 10 piercing"

  - name: "Head Hunter"
    desc: "  Any slashing weapon a dullahan wields becomes _[[Equipment/Keen|Keen]]_, and any hatchet it wields becomes _[[Equipment/Returning|Returning]]_. If the dullahan kills a creature with a critical hit using a slashing weapon, the target is decapitated as though the dullahan had used Reap on the target. These effects remain only while the dullahan holds the weapon."

  - name: "Headshot Hunter"
    desc: "  Any firearm wielded by the headless rustler becomes _keen_ (even if it's not a slashing weapon) and _striking_. If the headless rustler kills a creature with a critical hit using a firearm, the target is treated as if they were decapitated by the headless rustler's Reap ability. These effects remain only while the headless rustler holds the firearm."

  - name: "Reap"
    desc: "`pf2:2`  The dullahan removes the head of a dead creature within reach. Each creature within the area of the dullahan's frightful presence must attempt a new save, even if they are temporarily immune."

  - name: "Summon Steed"
    desc: "`pf2:2` (occult) The dullahan summons a [[Monster Core/War Horse|War Horse]] with elite adjustments and the fiend trait. This steed remains until it is slain, the dullahan Dismisses it, or the dullahan summons another steed."

  - name: "Throw Skull"
    desc: "`pf2:2` (manipulate) **Frequency** once (until a new clockwork skull is crafted)\n* * *\n\n**Effect** The headless rustler throws its clockwork skull at a target within 30 feet. The skull explodes, dealing 8d6 fire damage to creatures in a 15-foot radius (DC 23 Reflex check)."
 
```

```encounter-table
name: Headless Rustler
creatures:
  - 1: Headless Rustler
```


Variant dullahans

Riding on a horse as black as night, the headless hunter known as the dullahan tracks down and takes the heads of those it deems unfit to continue living. When closing in for the kill, the dullahan first whispers its victim's name, then swiftly collects its prize, casting a pall of dread upon all who witness the grim execution.

A dullahan manifests when a particularly violent warrior is beheaded and the warrior's soul stubbornly clings to material existence (or is refused entry to the afterlife). Most dullahans return to their former homelands, where they can exact vengeance those they feel wronged them in life (or their living descendants). A dullahan's concept of justice is swift and merciless, and once it has selected a target, it is unwavering in its cause.

Perhaps even more than revenge on the living, a dullahan desires its own rotted head. An individual who wields the head of a dullahan is powerful indeed, for a dullahan will grudgingly serve such a master in the hopes of reclaiming its missing skull. Mighty fiends such as devils command dullahans to harvest souls or lead armies for them, while a mortal might use such an undead warrior to fulfill a personal vendetta. No matter its master's rank or station, however, a dullahan won't hesitate to kill its liege and reclaim its head when the opportunity presents itself.

Most dullahan lairs are abandoned, overgrown ruins or other dilapidated places where severed heads and other trophies line the walls. Some dullahans, on the other hand, are content to simply commit their foul deeds and leave the remains of their decapitated victims in the streets, strewn among a copse of dead trees, or unceremoniously tossed in a bog hole.
