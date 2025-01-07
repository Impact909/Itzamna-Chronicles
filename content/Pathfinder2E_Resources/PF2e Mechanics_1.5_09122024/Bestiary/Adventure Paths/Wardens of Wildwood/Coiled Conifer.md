---
title: "Coiled Conifer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CqAo6PsN5rWipQBM" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/mutant
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Coiled Conifer"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Coiled Conifer"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[mutant]]
trait_03: [[plant]]
trait_04: [[wood]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27, Stealth: +24"
abilityMods: [8, 5, 7, -4, 2, -1]
speed: 20 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +22, __Will__ +19"
hp: 238
health:
  - name: ""
  - name: HP
    desc: "238; __Immunities__  acid,  poison; __Weaknesses__ axe vulnerability 15, fire 15; __Resistances__ bludgeoning 15, piercing 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Regurgitate Sap"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the coiled conifer attempts to [[Actions/Escape|Escape]]\n* * *\n\n**Effect** Sticky, caustic sap wells up in the conifer's maw. The DC of the Escape check increases by 2, and the creature takes 3d12 acid damage (DC 33 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Branchy Maw"
    desc: "+27 (deadly d10, reach 15 feet)\n__Damage__  3d10 + 14 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Root"
    desc: "+27 (agile, reach 15 feet, trip)\n__Damage__  3d8 + 14 bludgeoning plus push"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d10+9 bludgeoning, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Sap Spray"
    desc: "`pf2:2` (primal) The coiled conifer spews bile-like sap in a 60-foot cone. Creatures in the area take 7d12 acid damage (DC 33 Reflex check save) and become [[Conditions/Sickened|Sickened 1]] ([[Conditions/Sickened|Sickened 2]] on a critical failure).\n\nThe coiled conifer can't use this ability again for 1d4 rounds."

  - name: "Slithering Roots"
    desc: "`pf2:1`  **Requirements** The coiled conifer has at least one creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The coiled conifer Strides up to its full Speed, taking any creatures it has grabbed with it."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 3d6+9 bludgeoning, Rupture 24\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Coiled Conifer
creatures:
  - 1: Coiled Conifer
```



This bent and slithering entity is barely identifiable as a tree. Tentacle-like roots extend from its trunk in odd places, meeting tumorous knots filled with caustic sap.

* * *

The Plane of Wood contains many unique ecosystems formed around species of wondrous trees; when Ayrzul's Blight mutates one of these trees rather than killing it, it can have a cascading effect on the tree's biome. Multiple species often mutate in tandem, becoming warped mockeries and a vector for Ayrzul's Blight. These "blight bonded" creature families are parasites and predators and typically form twisted symbiotic relationships.
