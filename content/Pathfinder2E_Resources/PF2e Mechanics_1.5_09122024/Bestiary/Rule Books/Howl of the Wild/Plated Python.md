---
title: "Plated Python"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VIuappqHsOFZUOfi" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Plated Python"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Plated Python"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +25"
abilityMods: [7, 4, 6, -3, 6, 3]
speed: 40 feet,  burrow 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +20, __Will__ +22"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  petrified"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (reach 15 feet)\n__Damage__  3d10 + 10 piercing plus grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+24 (reach 15 feet)\n__Damage__  3d8 + 10 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d10+10 bludgeoning, DC 32 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crumbling Earth"
    desc: "`pf2:2` (earth,primal) The plated python lets its breath sink into the ground, transforming it to brittle stone within a 30-foot emanation. The stone is difficult terrain to all other creatures. Other creatures on the ground in this area when it transforms must succeed at a DC 29 Reflex check save or be [[Conditions/Immobilized|Immobilized]] as the stone beneath them crumbles to rubble. A creature immobilized in this way can [[Actions/Escape|Escape]] normally or use three total Interact actions to dig themself free."

  - name: "Petrify Prey"
    desc: " (earth,incapacitation,primal) **Requirements** The plated python has a creature [[Conditions/Grabbed|Grabbed]]\n\n**Trigger** The plated python begins its turn\n* * *\n\n**Effect** The python's breath seeps into the grabbed creature. That creature must attempt a DC 32 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature's body hardens and stiffens, causing it to become [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Petrified|Petrified]] for 1 round and Swallowed Whole.\n\n**Critical Failure** The creature is petrified permanently and Swallowed Whole."

  - name: "Stone Tunnel"
    desc: "  When a plated python burrows through ground, it petrifies and destroys the material in front of it, leaving a 5-foot diameter tunnel in its wake. A plated python doesn't need to [[Actions/Squeeze|Squeeze]] to pass through any space at least that wide."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d10+5 acid, Rupture 20\n* * *\n\nThis damage ignores the hardness of petrified creatures.\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Towering Bite"
    desc: "`pf2:2`  The plated python lunges to its full length, making a jaws Strike with a reach of 60 feet. If the Strike hits, its target is [[Conditions/Grabbed|Grabbed]] and pulled to an empty space adjacent to the plated python. The python can attack through any material it can burrow through, leaving a stone tunnel as normal."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Plated Python
creatures:
  - 1: Plated Python
```




