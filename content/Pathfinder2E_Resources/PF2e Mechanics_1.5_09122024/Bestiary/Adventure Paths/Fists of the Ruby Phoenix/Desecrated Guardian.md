---
title: "Desecrated Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a7BfNfmutQVaBf8Z" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Desecrated Guardian"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #168: King of the Mountain"
name: "Desecrated Guardian"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Lifesense 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +35, Stealth: +31"
abilityMods: [10, 6, 9, -5, 5, -5]
speed: 40 feet,  climb 40 feet
sourcebook: "_Pathfinder #168: King of the Mountain_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +36, __Ref__ +31, __Will__ +25"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360; __Immunities__  cold,  fire,  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Desecration Aura"
    desc: " (aura,divine) 40 feet. Desecrated guardians exude a palpable malice that nauseates all but the most wicked passersby. Non-evil creatures that enter the aura must attempt a DC 37 Will check save. On a failure, the creature becomes [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure). In addition, any non-evil creatures that attempt to Cast a Spell within the aura must succeed at a DC 5 Flat check check or the spell is lost."

  - name: "Rebuild"
    desc: "`pf2:2` (divine,earth,healing) The desecrated guardian draws in rubble from the surrounding area to rebuild its damaged body. It recovers 8d6 Hit Points. It can only use this ability if it is near suitable rock or rubble."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (deadly 3d12, magical, reach 20 feet)\n__Damage__  3d10 + 22 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (magical, reach 30 feet)\n__Damage__  3d8 + 20 bludgeoning plus improved-grab"

  - name: "Avalanche"
    desc: "`pf2:2`  The desecrated guardian thrashes its body about, causing the nearby terrain to crumble and crash down on creatures in a 60-foot cone, dealing 12d10 bludgeoning damage (DC 42 Reflex check save). It can't use Avalanche again for 1d4 rounds."

  - name: "Coiled Rockslide"
    desc: "  If the desecrated guardian started its turn hidden, it can Trample and remain hidden until after its attacks."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+18 bludgeoning damage, DC 39 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d8+20 bludgeoning damage, Rupture 45\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, tail, DC 37 Reflex check save\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Desecrated Guardian
creatures:
  - 1: Desecrated Guardian
```



Countless temples across Golarion, dedicated to deities both living and forgotten, have risen and fallen through the ages. Many find themselves buried under sand, snow, or vine never to be found. In such places, the spirits of the faithful can bind with their ruined temple to form a guardian construct, though with nothing left to guard, these spirits often become hollow, resentful, and filled with malice. These "desecrated guardians" lie in wait, sometimes for centuries, and destroy any adventurers who happen upon them. The most powerful desecrated guardians, such as the one presented here, incorporate the structures of multiple temples into their massive serpentine forms.
