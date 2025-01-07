---
title: "Warg"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.O2zXLkycOZJOouFX" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Warg"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Warg"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Goblin, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Deception: +6, Intimidation: +6, Stealth: +7, Survival: +8"
abilityMods: [4, 3, 3, -1, 2, 2]
speed: 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +9, __Will__ +6"
hp: 36
health:
  - name: ""
  - name: HP
    desc: "36"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Avenging Bite"
    desc: "`pf2:r`  **Trigger** A creature within reach of the warg's jaws attacks one of the warg's allies.\n* * *\n\n**Effect** The warg makes a jaws Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d8 + 4 piercing plus grab"

  - name: "Pack Attack"
    desc: "  The warg's Strikes deals an extra 1d4 damage to any creature within reach of at least two of the warg's allies."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Small, 1d6+2 bludgeoning, Rupture 9\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Warg
creatures:
  - 1: Warg
```



Wargs hunt in packs like wolves, but their penchant for taunting victims makes them easy to distinguish from their cousins. Orcs and hobgoblins frequently recruit wargs. Most wargs are amenable to this arrangement, but if food should run out, wargs are more than willing to integrate goblinoid flesh into their diet.

* * *

The warg is an intelligent and malevolent wolf that dwells among goblins, hobgoblins, orcs, and violent humanoids.
