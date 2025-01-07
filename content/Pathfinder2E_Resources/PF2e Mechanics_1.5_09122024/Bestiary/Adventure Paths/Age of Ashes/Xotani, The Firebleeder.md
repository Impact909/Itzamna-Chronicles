---
title: "Xotani, The Firebleeder"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5rfMKHhGFwAcMXbh" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Xotani, The Firebleeder"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Xotani, The Firebleeder"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fire]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Darkvision"
languages: "Aklo; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Athletics: +41"
abilityMods: [10, 8, 9, -4, 7, 6]
speed: 60 feet,  burrow 40 feet,  climb 60 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +36, __Ref__ +33, __Will__ +30"
hp: 385
health:
  - name: ""
  - name: HP
    desc: "385, regeneration 25; __Immunities__  clumsy,  disease,  drained,  enfeebled,  fire,  mental,  paralyzed,  petrified,  poison,  polymorph,  stupefied; __Weaknesses__ cold 22; __Resistances__ electricity 22, physical 22, sonic 22"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 25]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Firebleed"
    desc: "`pf2:r` (fire) **Trigger** Xotani is damaged\n* * *\n\n**Effect** Xotani's wound erupts with magma in a 30-foot cone, dealing 6d8 fire damage and 6d8 persistent fire damage (DC 42 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 300 feet. DC 39 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Light Blindness"
    desc: "  Xotani's light blindness is caused by only sunlight."

  - name: "Reactive"
    desc: "  Xotani gains 3 reactions each round. It can still use only one reaction per trigger."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (reach 20 feet)\n__Damage__  5d10 + 8 piercing 2d10 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, reach 20 feet)\n__Damage__  5d8 + 8 slashing 2d8 fire"

  - name: "**Ranged** `pf2:1` Lava Bomb"
    desc: "+38 (range increment 80 feet)\n__Damage__  2d10 + 8 bludgeoning 2d10 fire"

  - name: "Bomb Barrage"
    desc: "`pf2:2`  Xotani makes three lava bomb Strikes. These Strikes can be made against the same creature or different creatures, as long as all targets are within 40 feet of each other."

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) Xotani breathes a blast of flame that deals 18d6 fire damage plus 4d6 persistent fire damage to all creatures in a 70-foot cone (DC 42 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 8d6+8 bludgeoning + 12d6 fire, Rupture 35\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, claw, DC 42 Reflex check save. When Xotani Tramples, it can Stride up to triple its Speed.\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Xotani, The Firebleeder
creatures:
  - 1: Xotani, The Firebleeder
```



A monstrosity of living flame and magma, Xotani may be the weakest of Rovagug's spawn, but it remains a formidable threat. Xotani was slain in 2104 AR by an alliance of spellcasters, but recently its deathlike slumber was interrupted. Its corpse twitches, signaling that it might be close to returning.

* * *

The spawn are titanic terrors of immense size and strength that live only to destroy. Tarrasque and Xotani are but two of Rovagug's spawn. Others, including Chemnosit (the Monarch Worm), Kothogaz (the Dance of Disharmony), and Volnagur (the End-Singer) hold places of horror in the history of various regions, but the most famed is Ulunat (the Unholy First), whose beetle-like carcass remains sprawled in Sothis, the capital of Osirion.
