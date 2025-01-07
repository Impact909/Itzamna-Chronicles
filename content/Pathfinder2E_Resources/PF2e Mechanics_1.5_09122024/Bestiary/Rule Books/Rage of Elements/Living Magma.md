---
title: "Living Magma"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.eqa5WuWokxNr72y3" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Living Magma"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Living Magma"
level: "Creature 13"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[fire]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Pyric"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Intimidation: +23, Stealth: +22"
abilityMods: [8, 5, 5, 4, 5, 4]
speed: 40 feet,  swim 60 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +26, __Ref__ +20, __Will__ +22"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Immunities__  bleed,  paralyzed,  fire,  sleep,  poison; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Molten Form"
    desc: " (fire) Any creature that hits the living magma with an unarmed Strike or otherwise touches it takes 10 fire damage. If a gallon or more of water touches the living magma, or if it's affected by a water effect, its outer layer of lava hardens to a rocky shell, deactivating its molten form and imposing weakness 15 to bludgeoning damage. Molten form reactivates if the living magma swims in lava for 1 minute."

  - name: "Trap Weapon"
    desc: "`pf2:r` (fire) **Frequency** once per round\n\n**Trigger** A creature hits the living magma with a melee weapon\n* * *\n\n**Effect** The living magma attempts an Athletics check check against the triggering creature's Athletics DC. On a success, the living magma traps the weapon in its body and pulls it from the attacker's grasp. A creature can Interact to retrieve the weapon, but the attempt fails unless the creature succeeds at an Athletics check check against the living magma's Fortitude DC (typically 36). If the living magma uses Engulf, it also absorbs all trapped weapons, rendering them unreachable until it dies."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Magma Fist"
    desc: "+27 (reach 20 feet)\n__Damage__  2d4 fire 3d6 fire 3d8 + 11 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 33 Reflex check, 2d10 bludgeoning + 4d6 fire damage, Escape DC 33, Rupture 25\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Launch Lava"
    desc: "`pf2:2` (fire) The living magma hurls an exploding glob of lava up to 120 feet. Each creature in a 10-foot burst takes 7d6 fire damage (DC 33 Reflex check save)."

  - name: "Reignite"
    desc: "`pf2:2` (fire) **Requirements** The living magma is not in molten form\n* * *\n\n**Effect** The living magma returns to molten form."

  - name: "Volcanic Heat"
    desc: " (aura,fire) 40 feet. Any creature that enters or starts its turn in the aura takes 15 fire damage (DC 33 Fortitude check save). A creature that fails its save is also [[Conditions/Enfeebled|Enfeebled 1]] until it's no longer in the aura."
 
```

```encounter-table
name: Living Magma
creatures:
  - 1: Living Magma
```



Living magmas can lie dormant for centuries below the earth before they awaken from their slumber in a fiery a volcanic eruption. This is especially dangerous when entire colonies of the molten elementals arise at the same time.

* * *

The ifrits of the Dominion of Flame conscript even more of the plane's fire elementals in preparation for new wars in the returned planes, even mobilizing ones that rarely travel near settlements.
