---
title: "Snapping Flytrap"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7RkKcrVZOdpQly5e" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Snapping Flytrap"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Snapping Flytrap"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[plant]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11, Stealth: +10"
abilityMods: [2, 3, 5, -5, 2, -2]
speed: 15 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +8, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  mental; __Weaknesses__ fire 5; __Resistances__ acid 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Quick Capture"
    desc: "`pf2:r`  **Trigger** A creature hits or touches the flytrap.\n* * *\n\n**Effect** The flytrap makes a leaf Strike against the triggering creature. If it hits, the creature is [[Conditions/Grabbed|Grabbed]] in that leaf."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Leaf"
    desc: "+11 (reach 10 feet)\n__Damage__  1d8 + 2 piercing plus improved-grab 1d6 acid plus improved-grab"

  - name: "Focused Assault"
    desc: "`pf2:2`  The flytrap attacks a single target with both its two leaves. The flytrap makes one leaf Strike. On a success, the flytrap deals the damage from one leaf Strike plus an additional 1d8 piercing damage for every leaf beyond the first. On a failure, the flytrap deals the damage from one leaf Strike, but it can't use Improved Grab. It deals no damage on a critical failure. This counts toward the flytrap's multiple attack penalty as a number of attacks equal to the number of leaves the flytrap has."

  - name: "Hungry Flurry"
    desc: "`pf2:2`  The flytrap makes two leaf Strikes at a -2 penalty, each against a different target. These attacks count toward the flytrap's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all its attacks."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 1d8+1 bludgeoning + 1d6 acid, Rupture 5\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Snapping Flytrap
creatures:
  - 1: Snapping Flytrap
```



Snapping flytraps typically have two sets of tooth-edged leaves, each measuring 3 feet wide, at the end of 10-foot-long stalks.

* * *

Flytraps eagerly feed on humanoids, monstrous insects, and larger prey.
