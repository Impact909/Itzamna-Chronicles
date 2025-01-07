---
title: "Witchwarg"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DmObCjk4Wv6CawRF" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/cold
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Witchwarg"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Witchwarg"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[cold]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +13, Deception: +11, Intimidation: +11, Stealth: +13, Survival: +12"
abilityMods: [6, 4, 4, 2, 3, 2]
speed: 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +13, __Ref__ +15, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Immunities__  cold; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Avenging Bite"
    desc: "`pf2:r`  **Trigger** A creature within reach of the witchwarg's jaws attacks one of the witchwarg's allies.\n* * *\n\n**Effect** The witchwarg makes a jaws Strike against the triggering creature."

  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 21 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (cold)\n__Damage__  1d10 + 6 piercing plus knockdown 1d6 cold plus knockdown"

  - name: "Pack Attack"
    desc: "  The witchwarg's Strikes deal 1d6 extra damage to creatures within the reach of at least two of the witchwarg's allies."

  - name: "Winter Breath"
    desc: "`pf2:2` (cold,primal) The witchwarg breathes a cloud of frost in a 15-foot cone that deals 5d8 cold damage (DC 23 Reflex check save).\n\nThe witchwarg can't use Winter Breath again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Witchwarg
creatures:
  - 1: Witchwarg
```



Witchwargs are related to wargs, but are larger, smarter, and far more dangerous. They are capable of exhaling plumes of freezing breath. When they deign to serve others, they usually reserve this privilege for more dangerous creatures, such as the winter witches of Irrisen.

* * *

The warg is an intelligent and malevolent wolf that dwells among goblins, hobgoblins, orcs, and violent humanoids.
