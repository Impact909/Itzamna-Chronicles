---
title: "Giant Snapping Turtle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YInrQFIoNKrGZMTN" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Giant Snapping Turtle"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Snapping Turtle"
level: "Creature 9"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +20"
abilityMods: [7, 0, 4, -4, 4, -2]
speed: 20 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +15, __Will__ +19"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The giant snapping turtle can hold its breath for 2 hours."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 ()\n__Damage__  2d12 + 10 piercing plus improved-grab"

  - name: "Capsize"
    desc: "`pf2:1` (attack,move) The turtle tries to capsize an adjacent aquatic vessel of its size or smaller. The turtle must succeed at a DC 35 Athletics check check (reduced by 5 for each size smaller the vessel is than the turtle) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Shell Defense"
    desc: "`pf2:1`  The giant snapping turtle retracts its limbs and head into its shell and ends its turn. This increases its AC to 30, but it can't act except to reemerge, which it can do as a single action."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d12+7 bludgeoning damage, Rupture 30\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Snapping Turtle
creatures:
  - 1: Giant Snapping Turtle
```



If the regular-sized snapping turtle is foul-tempered, then the giant snapping turtle seems to be willfully violent toward anything that dares intrude upon its domain. Measuring over 20 feet long and weighing thousands of pounds, this creature is capable of swallowing a humanoid whole. Swamp-dwelling societies, particularly boggards and lizardfolk, have often tried to domesticate giant snapping turtles to serve as powerful guardians, but in most cases the casualties pile up quickly. Those unfortunate enough to be swallowed whole by a giant snapping turtle find that even the creature's stomach is somewhat armored, making it difficult to cut through.
