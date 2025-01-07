---
title: "Benthic Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bjcdejpDuPnfRQpi" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Benthic Worm"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Benthic Worm"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +33, Stealth: +20"
abilityMods: [10, -1, 8, -5, -1, -1]
speed: 40 feet,  burrow 40 feet,  swim 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +32, __Ref__ +20, __Will__ +23"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Immunities__  immobilized"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Inexorable"
    desc: "  The benthic worm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Slough Skin"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The benthic worm would be affected by a condition or adverse effect (such as [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]])\n* * *\n\n**Effect** The benthic worm negates the triggering condition or effect by sloughing an outer layer of its skin. Effects from artifacts, deities, or a similarly powerful source can't be avoided in this way."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+31 (deadly 2d10, reach 15 feet)\n__Damage__  3d12 + 16 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+31 (agile, poison, reach 15 feet)\n__Damage__  4d6 + 16 piercing plus azure-worm-venom"

  - name: "**Melee** `pf2:1` Body"
    desc: "+29 (reach 15 feet)\n__Damage__  2d8 + 14 bludgeoning"

  - name: "Benthic Worm Venom"
    desc: " (poison) **Saving Throw** DC 37 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 4d6 poison damage and clumsy 2 (1 round)\n\n**Stage 3** 6d6 poison damage and clumsy 2 (1 round)"

  - name: "Breach"
    desc: "`pf2:2`  The benthic worm Swims up to its swim Speed, then [[Actions/Leap|Leaps]] vertically out of the water up to 30 feet, making a Strike against a creature at the apex of the jump (this lets it attack a creature within 45 feet of the water's surface). After the Strike, the worm splashes back down. It can use [[Bestiary Ability Glossary/Improved Grab|Improved Grab]] on this Strike and follow it up with Fast Swallow."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The worm [[Conditions/Grabbed|Grabs]] a creature.\n* * *\n\n**Effect** The worm uses Swallow Whole."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d8+10 bludgeoning, Rupture 27\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Thrash"
    desc: "`pf2:2`  The worm makes a Strike once against each creature in its reach. It can Strike up to once with its jaws, up to once with its stinger, and any number of times with its body. Each attack counts toward the worm's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Benthic Worm
creatures:
  - 1: Benthic Worm
```



The benthic worm is a deep-blue creature that is more at home in flooded tunnels than dry caves. While a benthic worm is a strong swimmer, it prefers to lie in wait within the walls, floor, or even ceiling of flooded caverns, ready to spring out and ambush creatures swimming past its hiding spot. The benthic worm is particularly hated and feared by Darklands-dwelling cultures, due to the fact that a benthic worm that burrows into a tunnel often brings with it waters from the submerged river or lake it calls home. When it becomes obvious that a benthic worm is near a Darklands settlement, the inhabitants quickly establish a hunting party to deal with the menace before it can bring ruin.

* * *

Cave worms are gigantic scavengers that bore through the depths of the world, eating whatever material they find. Named for their distinctive habitats, these worms are ravenous and display overwhelming destructive capabilities. Cave worms of different types and abilities lurk in the more remote corners of the world—tales speak of arctic worms that dwell within immense glaciers or icebergs and grave worms that burrow through the boneyards of long-forgotten ruins, to name a few.
