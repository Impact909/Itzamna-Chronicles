---
title: "Orochi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Wv9OieEbu2GmzZer" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Orochi"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Orochi"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[amphibious]]
trait_02: [[beast]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Low-Light Vision"
languages: "Aklo, Common, Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +36, Intimidation: +31, Survival: +29"
abilityMods: [10, 6, 10, 5, 4, 6]
speed: 30 feet,  swim 60 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 42
armorclass:
  - name: AC
    desc: "42 all-around vision; __Fort__ +33, __Ref__ +30, __Will__ +27"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400, HP (head) 60, multiple heads;; __Resistances__ poison 15"
abilities_top:
  - name: ""

  - name: "Multiple Heads"
    desc: "  A creature can attempt to sever one of the orochi's eight heads by specifically targeting it and dealing damage equal to the head's HP. A head not completely severed returns to full HP at the end of the attacking creature's turn. An orochi that loses all of their heads immediately dies."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 37 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Head: Weaknesses and Immunities"
    desc: "  **HP** 60, multiple heads\n\n**Immunities** area damage\n\n**Weaknesses** cold iron 15\n\n**Resistances** poison 15"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (reach 40 feet)\n__Damage__  3d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (agile, magical, reach 50 feet)\n__Damage__  3d10 + 18 bludgeoning plus improved-knockdown"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+34 (brutal, range increment 100 feet)\n__Damage__  3d8 + 18 bludgeoning"

  - name: "Multiple Opportunities"
    desc: "  The orochi gains an extra reaction per round for each of their heads that remains beyond the first, which it can use only to make Attacks of Opportunity. They can't use more than 1 reaction on the same triggering action, and the orochi must use a different head for each Attack of Opportunity."

  - name: "Orochi Flurry"
    desc: "`pf2:2`  The orochi makes a number of jaws Strikes equal to the number of their remaining heads, each against a different target. The orochi's multiple attack penalty doesn't increase until after the orochi makes all of their attacks."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 2d12+18 bludgeoning damage, Rupture 40\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Orochi
creatures:
  - 1: Orochi
```



An orochi is an enormous serpent with eight heads and eight tails that lives among large waterways. Orochi are vile, amoral creatures kept at bay only with yearly sacrifices. Most settlements unable to satisfy an orochi with a sacrifice soon meet their destruction.
