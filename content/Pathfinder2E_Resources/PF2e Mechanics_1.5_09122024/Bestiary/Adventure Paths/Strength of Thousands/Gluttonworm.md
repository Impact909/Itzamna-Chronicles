---
title: "Gluttonworm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AChTtLA2owKXb1Hi" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Gluttonworm"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Gluttonworm"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[beast]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Tremorsense (Imprecise) 100 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +37"
abilityMods: [10, 4, 6, -4, 5, -1]
speed: 30 feet,  burrow 40 feet
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +35, __Ref__ +29, __Will__ +32"
hp: 445
health:
  - name: ""
  - name: HP
    desc: "445, sand armor; __Immunities__  immobilized"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 100 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Dune Dispersal"
    desc: " (aura) 15 feet. Ground in the aura is greater difficult terrain."

  - name: "Inexorable"
    desc: "  The gluttonworm recovers from the [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], and [[Conditions/Stunned|Stunned]] conditions at the end of its turn.\n\nIt's also immune to penalties to its Speeds and the [[Conditions/Immobilized|Immobilized]] condition, and it ignores difficult terrain and greater difficult terrain."

  - name: "Sand Armor"
    desc: " (primal) A gluttonworm in contact with a significant body of sand, such as a desert or beach, gains fast healing 10.\n\nIf the gluttonworm is subject to persistent bleed, the flowing blood quickly congeals with the sand covering its body, instantly ending the bleed duration and giving the gluttonworm a +2 circumstance bonus to AC until the end of its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+37 (deadly 3d10, reach 20 feet)\n__Damage__  4d12 + 18 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Body"
    desc: "+33 ()\n__Damage__  4d8 + 18 bludgeoning"

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The gluttonworm Grabs a creature, or a creature fails a Reflex save against a Gulping Charge\n* * *\n\n**Effect** The gluttonworm uses Swallow Whole."

  - name: "Gulping Charge"
    desc: "`pf2:3`  The gluttonworm Strides up to double its Speed and can move through the spaces of Large or smaller creatures, gulping each creature whose space the worm enters and attempting a body Strike against each of them.\n\nThe gluttonworm can use this Strike on each creature only once in a single use of Gulping Charge. Creatures can attempt a DC 41 Reflex check save against this damage."

  - name: "Spew Sandstorm"
    desc: "`pf2:3` (air,earth,primal) The gluttonworm exhales swirling sand in a 60-foot cone. Creatures in the area must attempt a DC 41 Reflex check save.\n\nIt can't Spew Sandstorm again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d6 slashing damage and 4d6 bludgeoning damage from the scouring sand.\n\n**Failure** The creature takes 8d6 slashing damage and 8d6 bludgeoning damage from the sand, and is [[Conditions/Dazzled|Dazzled]] until the end of its next turn.\n\n**Critical Failure** The creature takes 12d6 slashing damage and 12d6 bludgeoning damage and is [[Conditions/Blinded|Blinded]] for 1 hour."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+17 bludgeoning and 2d6 slashing, Rupture 36\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Gluttonworm
creatures:
  - 1: Gluttonworm
```



Akiton's gluttonworms share many features of Golarion's cave worms, yet these immense predators are their own distinct species. Gluttonworms "swim" through the vast deserts of Akiton, moving almost like whales through the ocean as they forage for their next meals.
