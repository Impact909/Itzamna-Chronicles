---
title: "Tarrasque, The Armageddon Engine"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JvJv4PwwLK9VjjNd" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/25
statblock: inline
name: "Tarrasque, The Armageddon Engine"
level: 25
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Tarrasque, The Armageddon Engine"
level: "Creature 25"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[unholy]]
modifier: 48
perception:
  - name: "Perception"
    desc: "+48; Darkvision, Scent (Imprecise) 120 Feet"
languages: "Aklo; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +47, Athletics: +50"
abilityMods: [12, 9, 12, -3, 9, 7]
speed: 50 feet,  swim 50 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 54
armorclass:
  - name: AC
    desc: "54; __Fort__ +47, __Ref__ +37, __Will__ +39; +2 status to all saves vs. magic"
hp: 540
health:
  - name: ""
  - name: HP
    desc: "540, regeneration 50; __Immunities__  acid,  clumsy,  disease,  drained,  enfeebled,  mental,  paralyzed,  petrified,  polymorph,  poison,  stupefied; __Resistances__ fire 25, physical 25"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 50]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Carapace"
    desc: "  Tarrasque is immune to cones, lines, rays, and magic missile spells. These effects bounce harmlessly off its scales."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 300 feet. DC 39 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Inexorable"
    desc: "  Tarrasque recovers from the [[Conditions/Slowed|Slowed]] and [[Conditions/Stunned|Stunned]] conditions at the end of its turn. It's also immune to penalties to its Speeds, and it ignores difficult terrain and greater difficult terrain."

  - name: "Reactive"
    desc: "  Tarrasque gains 3 reactions each round. It can still use only one reaction per trigger."

  - name: "Reflect"
    desc: "`pf2:r`  **Trigger** Tarrasque's carapace deflects an effect.\n* * *\n\n**Effect** The effect is redirected back at its source."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+45 (magical, reach 20 feet, unholy)\n__Damage__  5d12 + 20 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+45 (agile, magical, reach 15 feet, unholy)\n__Damage__  5d10 + 20 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+45 (magical, reach 30 feet, unholy)\n__Damage__  4d12 + 20 bludgeoning"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+45 (magical, reach 15 feet, unholy)\n__Damage__  4d10 + 20 piercing"

  - name: "**Ranged** `pf2:1` Spine"
    desc: "+45 (brutal, magical, range increment 120 feet, unholy)\n__Damage__  3d10 + 20 piercing"

  - name: "Destructive Frenzy"
    desc: "`pf2:3`  Tarrasque makes a jaws Strike, two claw Strikes, two horn Strikes, and one tail Strike in any order."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** Tarrasque Grabs a creature with its jaws\n* * *\n\n**Effect** Tarrasque uses Swallow Whole."

  - name: "Spine Volley"
    desc: "`pf2:2`  Tarrasque flings spines in a 120-foot cone, dealing 3d10+20 piercing damage to each creature in the area (DC 53 Reflex check save).\n\nTarrasque can't use Spine Volley again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 10d6+12 bludgeoning + 10d6 acid, Rupture 50\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, claw, DC 49 Reflex check save. When Tarrasque Tramples, it can Stride up to triple its Speed.\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tarrasque, The Armageddon Engine
creatures:
  - 1: Tarrasque, The Armageddon Engine
```



The most powerful spawn is Tarrasque, whose legend spread across countless worlds beyond Golarion. Its destruction of the nation of Ninshabur and its march across Avistan in -632 AR culminated in the destruction of the flying Shory city of Kho before this spawn was sealed away in a remote cavern.

* * *

The spawn are titanic terrors of immense size and strength that live only to destroy. Tarrasque and Xotani are but two of Rovagug's spawn. Others, including Chemnosit (the Monarch Worm), Kothogaz (the Dance of Disharmony), and Volnagur (the End-Singer) hold places of horror in the history of various regions, but the most famed is Ulunat (the Unholy First), whose beetle-like carcass remains sprawled in Sothis, the capital of Osirion.
