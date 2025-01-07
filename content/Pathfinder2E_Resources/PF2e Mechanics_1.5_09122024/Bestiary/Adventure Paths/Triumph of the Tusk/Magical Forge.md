---
title: "Magical Forge"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0amcXEPCuFz9NAvb" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Magical Forge"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Magical Forge"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +20"
abilityMods: [7, -2, 6, -5, 0, -5]
speed: 15 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 28
armorclass:
  - name: AC
    desc: "28 (24 when broken); construct armor; __Fort__ +19, __Ref__ +9, __Will__ +11"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Hardness__ 8; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Construct Armor (Hardness 8)"
    desc: "  Like normal objects, an animated furnace has Hardness. This Hardness reduces any damage the furnace takes by an amount equal to the Hardness. Once an animated furnace is reduced to fewer than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks, removing the Hardness and reducing its Armor Class to 24."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Door"
    desc: "+21 (magical)\n__Damage__  2d12 + 7 bludgeoning plus improved-grab 1d8 fire plus improved-grab"

  - name: "Fan the Flames"
    desc: "`pf2:2`  The animated furnace opens its door and fans its flames in a 30-foot cone that deals 5d6 fire damage (DC 28 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d8+9 fire, Rupture 15\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Magical Forge
creatures:
  - 1: Magical Forge
```


Weak animated furnace

This huge forge or oven is animated to protect a workspace or kitchen, travel alongside its owner, or both.

* * *

Many animated objects have useful functions but become dangers when uncontrolled.
