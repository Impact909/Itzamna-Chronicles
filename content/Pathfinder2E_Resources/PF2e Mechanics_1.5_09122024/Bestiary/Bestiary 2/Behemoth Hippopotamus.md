---
title: "Behemoth Hippopotamus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HauaBRCkBKPtwxah" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Behemoth Hippopotamus"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Behemoth Hippopotamus"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23, Stealth: +18, Survival: +17"
abilityMods: [7, 4, 7, -4, 5, -2]
speed: 35 feet,  swim 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +22, __Ref__ +17, __Will__ +19"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The behemoth hippopotamus can hold its breath for 1 hour."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (deadly d12, reach 10 feet)\n__Damage__  2d12 + 10 piercing plus grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+21 ()\n__Damage__  2d8 + 9 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  40 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The behemoth hippopotamus tries to capsize an adjacent aquatic vessel of its size or smaller. The behemoth hippopotamus must succeed at an Athletics check with a DC of 30 (reduced by 5 for each size smaller the vessel is than the hippo) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Double Chomp"
    desc: "`pf2:1`  The behemoth hippo makes a jaws Strike targeting two creatures adjacent to each other. Roll the attack and damage once, and apply it to each creature separately. A Double Chomp counts as two attacks for the multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d12+10 bludgeoning damage, Rupture 26\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, foot, DC 29 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Behemoth Hippopotamus
creatures:
  - 1: Behemoth Hippopotamus
```



Behemoth hippopotamuses stand taller than elephants. They spend less time out of water than their smaller kin. Behemoth hippos are omnivorous, and many enjoy the taste of meat.