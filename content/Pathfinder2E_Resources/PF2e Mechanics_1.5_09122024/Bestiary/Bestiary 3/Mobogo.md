---
title: "Mobogo"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M8BAwTyUXGXcBS2y" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Mobogo"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Mobogo"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[beast]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Boggard; speak with animals"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +23, Nature: +21, Stealth: +19"
abilityMods: [7, 5, 6, -2, 5, 7]
speed: 25 feet,  fly 20 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +22, __Ref__ +17, __Will__ +19"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160, regeneration 30 (deactivated by acid, cold, or fire)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 30 (Deactivated by Acid, Cold, or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (reach 10 feet)\n__Damage__  2d12 + 13 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+23 (agile, reach 30 feet)\n__Damage__  2d6 + 13 bludgeoning plus tongue-grab"

  - name: "Primal Innate Spells"
    desc: "DC 27, attack +19; __5th __  _[[Spells/Control Water|Control Water]]_; __4th __  _[[Spells/Create Water|Create Water (At Will)]]_, _[[Spells/Entangling Flora|Entangle]]_, _[[Spells/Mist|Obscuring Mist]]_, _[[Spells/Noise Blast|Sound Burst (At Will)]]_\n__Constant__  __(2nd)__ _[[Spells/Vanishing Tracks|Pass Without Trace]]_, _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Rituals"
    desc: "_Plant Growth_"

  - name: "Song of the Swamp"
    desc: "`pf2:1` (auditory,emotion,mental,primal) **Frequency** once per 10 minutes\n* * *\n\n**Effect** The mobogo unleashes a booming croak. All boggards and mobogos within 50 feet gain a +2 status bonus to damage rolls and saves against fear for 1 round. Other creatures in the area of effect must attempt a DC 27 Will check save.\n* * *\n\n**Success** The creature is unaffected and is temporarily immune for 24 hours.\n\n**Failure** The creature is [[Conditions/Slowed|Slowed 1]] for 1d4 rounds.\n\n**Critical Failure** The creature is [[Conditions/Slowed|Slowed 2]] for 1d4 rounds.\n\n[[Bestiary Effects/Effect_ Song of the Swamp|Effect: Song of the Swamp]]"

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d12+6 bludgeoning, Rupture 19\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Swamp Stride"
    desc: "  A mobogo ignores difficult terrain caused by swamp terrain features."

  - name: "Tongue Grab"
    desc: "  A creature hit by the mobogo's tongue becomes [[Conditions/Grabbed|Grabbed]] by the mobogo. The creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the mobogo's tongue.\n\nA creature can sever the tongue with a Strike against AC 27 that deals at least 10 slashing damage. This deals no damage to the mobogo but prevents it from using its tongue Strike until it regrows its tongue, which takes 1 round.\n\nThe mobogo can move without ending the Grab as long as the creature remains within the tongue's reach."

  - name: "Tongue Reposition"
    desc: "`pf2:1`  The mobogo attempts to move a creature [[Conditions/Grabbed|Grabbed]] by its tongue. The mobogo rolls an Athletics check check against the creature's Fortitude DC.\n\nOn a success, the mobogo moves the creature into any space within the tongue's reach. If it wishes, the mobogo can transfer the grabbed creature to its jaws."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mobogo
creatures:
  - 1: Mobogo
```



Mobogos are massive, swamp-dwelling monstrosities that combine the worst aspects of giant toads and evil dragons. Lazy, cruel, and greedy, these vile creatures make their lairs in the most ancient and primordial swamps. The boggards who call such places home worship mobogos as living demigods, regularly bringing sacrifices of food and valuables lest they become the next victims of the mobogos' boundless appetites.
