---
title: "Elemental Thicket"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BDyJLHXs8OJaFdfg" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Elemental Thicket"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Elemental Thicket"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +23"
abilityMods: [7, 4, 6, 1, 2, 1]
speed: 25 feet,  burrow 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +13, __Will__ +25"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240, regeneration 15 (deactivated by fire); __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ axe vulnerability 10, fire 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Regeneration 15 (Deactivated by Fire)"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gnarled Branch"
    desc: "+24 (reach 20 feet)\n__Damage__  2d12 + 7 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+7 bludgeoning, DC 30 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 30 Reflex check, 8d10 bludgeoning damage, Escape DC 27, Rupture 20\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Entangling Growth"
    desc: " (aura,plant,primal) 30 feet.\n\nPlant life erupts out of any and all soil surrounding the elemental thicket, making the area greater difficult terrain out to 5 feet and difficult terrain out to 30 feet. This ability requires soil and has no effect on terrain without it, such as worked stone, solid rock, open water, etc."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Elemental Thicket
creatures:
  - 1: Elemental Thicket
```



In the Universe, plant growth proceeds on a scale of days, weeks, years, and decades. Conversely, an elemental thicket grows constantly and in seconds. These writhing masses of living wood are the elemental embodiment of growth itself, swelling up when least expected to consume all in their path.
