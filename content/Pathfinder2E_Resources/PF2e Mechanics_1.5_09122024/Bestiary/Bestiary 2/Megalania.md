---
title: "Megalania"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yxpX0HkryPk75IsX" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Megalania"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Megalania"
level: "Creature 7"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +15"
abilityMods: [7, 2, 4, -4, 2, -2]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +15, __Will__ +13"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (reach 10 feet)\n__Damage__  2d10 + 9 piercing plus grab,megalania-venom"

  - name: "Megalania Venom"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 3]], and [[Conditions/Off-Guard|Off-Guard]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d10+7 bludgeoning, Rupture 16\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Megalania
creatures:
  - 1: Megalania
```



Megalanias, like their smaller cousins the giant monitor lizards, strike fast and use their powerful bite to grip their prey. They prefer to swallow their prey whole rather than risk others getting a bite of a hard-won meal.
