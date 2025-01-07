---
title: "Tylosaurus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YdIlb0aIuGBNSwO9" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Tylosaurus"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Tylosaurus"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +19, Stealth: +19"
abilityMods: [7, 5, 5, -4, 4, -2]
speed: 5 feet,  swim 80 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +19, __Will__ +14"
hp: 137
health:
  - name: ""
  - name: HP
    desc: "137"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  A tylosaurus can hold its breath for 2 hours."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 ()\n__Damage__  2d12 + 10 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 ()\n__Damage__  2d6 + 10 bludgeoning"

  - name: "Aquatic Drag"
    desc: "`pf2:1`  **Requirements** The tylosaurus has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The tylosaurus Swims up to half its Speed, carrying the grabbed creature with it."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d6+5 bludgeoning, Rupture 18\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Vicious Strafe"
    desc: "`pf2:2`  The tylosaurus Swims up to its Speed. It can make one jaws Strike and one tail Strike at any points during its movement, each attacking a different target."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tylosaurus
creatures:
  - 1: Tylosaurus
```



Though large in size-sometimes exceeding 40 feet-tylosauruses have sleek bodies and long, narrow snouts. Few creatures compete with them in their environment, as most other aquatic giants reside in deeper water.

* * *

The massive swimming reptiles called mosasaurs thrash their powerful tails to propel them after prey. Four articulated, webbed paddles let them precisely steer their paths, and their hinged jaws-much like a snake's-allow mosasaurs to swallow larger creatures than their size would indicate. A small set of secondary pterygoid jaws in their gullets pull in their meals for more efficient digestion. As air breathers, mosasaurs must stay near the surface of the water, competing for food with whales. This proximity to the surface means they often capsize small boats, feasting on the crew members who fall out.
