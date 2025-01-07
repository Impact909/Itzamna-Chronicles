---
title: "Giant Toad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W7ZTv0oNZu5rkDoA" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Giant Toad"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Toad"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9, Stealth: +6"
abilityMods: [5, 2, 3, -4, 2, -2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +9, __Ref__ +8, __Will__ +6"
hp: 36
health:
  - name: ""
  - name: HP
    desc: "36"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Poisonous Warts"
    desc: "  Any creature that hits the giant toad with an unarmed Strike or otherwise touches the toad is exposed to giant toad poison."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+11 ()\n__Damage__  1d8 + 5 piercing plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+11 (reach 10 feet)\n__Damage__ "

  - name: "Giant Toad Poison"
    desc: " (poison) **Saving Throw** DC 19 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 2** [[Conditions/Stupefied|Stupefied 1]] and [[Conditions/Confused|Confused]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 1d8+2 bludgeoning damage, Rupture 8\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Tongue Grab"
    desc: "  A creature hit by the giant toad's tongue becomes [[Conditions/Grabbed|Grabbed]] by the giant toad. The creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the toad's tongue. A creature can sever the tongue with a successful Strike against AC 15 that deals at least 6 slashing damage.\n\nThis deals no damage to the toad but prevents it from using its tongue Strike until it regrows its tongue, which takes a week."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Toad
creatures:
  - 1: Giant Toad
```



Most giant toads live in dry environments, particularly deserts, and eagerly eat almost any creature smaller than themselves. They're known to eat giant rats, then take over the rats' burrows as homes. Giant toads have large poison glands behind their eyes that enable them to coat their skin with poison. This leads to them having very few natural predators, and populations can quickly explode if left unchecked. While most consider giant toads dangerous pests, some groups of ogres and hill giants cultivate them to collect their poison for recreational use.
