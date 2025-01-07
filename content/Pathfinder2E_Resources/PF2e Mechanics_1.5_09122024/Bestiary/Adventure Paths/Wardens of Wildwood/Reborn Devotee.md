---
title: "Reborn Devotee"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Nm2pZC554qG2ft4Q" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2e/creature/type/mutant
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Reborn Devotee"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Reborn Devotee"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[fungus]]
trait_02: [[mindless]]
trait_03: [[mutant]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +25, Stealth: +23"
abilityMods: [7, 5, 5, -5, 3, -2]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +21, __Ref__ +19, __Will__ +17"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  mental; __Weaknesses__ fire 10; __Resistances__ acid 10, poison 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Quick Capture"
    desc: "`pf2:r`  **Trigger** A creature hits or touches the reborn devotee\n* * *\n\n**Effect** The reborn devotee makes a stalk Strike against the triggering creature. If it hits, the creature is [[Conditions/Grabbed|Grabbed]] in that stalk."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stalk"
    desc: "+25 (reach 15 feet)\n__Damage__  2d8 + 9 piercing plus improved-grab 2d6 acid plus improved-grab"

  - name: "Focused Assault"
    desc: "`pf2:2`  The reborn devotee attacks a single target with four stalks, making one stalk Strike. On a success, the reborn devotee deals the damage from one stalk Strike plus an additional 1d8 damage for every stalk beyond the first. On a failure, the reborn devotee deals the damage from one stalk Strike, but it can't use Improved Grab. It deals no damage on a critical failure. This counts toward the reborn devotee's multiple attack penalty as a number of attacks equal to the number of stalks the devotee has."

  - name: "Hungry Flurry"
    desc: "`pf2:2`  The reborn devotee makes four stalk Strikes at a –2 penalty, each against a different target. These attacks count toward the reborn devotee's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all its attacks."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d8+5 bludgeoning + 2d6 acid, Rupture 17\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Reborn Devotee
creatures:
  - 1: Reborn Devotee
```




