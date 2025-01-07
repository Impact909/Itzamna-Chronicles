---
title: "Zaramuun"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kghO1FwqzArtFxjN" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Zaramuun"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Zaramuun"
level: "Creature 16"

alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[earth]]
trait_03: [[elemental]]
trait_04: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Chthonian, Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Religion: +26, Stealth: +27"
abilityMods: [9, 5, 6, 0, 5, -1]
speed: 35 feet,  burrow 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +34, __Ref__ +30, __Will__ +25"
hp: 291
health:
  - name: ""
  - name: HP
    desc: "291; __Immunities__  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+33 ()\n__Damage__  4d12 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock Or Metal Debris"
    desc: "+29 (range increment 120 feet)\n__Damage__  4d8 + 13 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +31; __6th __  _[[Spells/Disintegrate|Disintegrate]]_, _[[Spells/Spirit Blast|Spirit Blast]]_; __4th __  _[[Spells/Suggestion|Suggestion (At Will)]]_\n__Constant__  __(8th)__ _[[Spells/Planar Tether|Dimensional Anchor (At Will)]]_"

  - name: "Rituals"
    desc: "_Planar Ally_"

  - name: "Dune"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the zaramuun appears to be a sand dune. It has an automatic result of 47 (50 in sandy terrain) on Deception and Stealth checks and DCs to pass as a sand dune. Any creature that walks onto the zaramuun moves into its body and is Engulfed."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 35 Reflex check, 4d12 bludgeoning damage and [[Spells/Planar Tether|Planar Tether]], Escape DC 32, Rupture 28\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Raking Sand"
    desc: "`pf2:1`  **Requirements** The zaramuun hit with a melee Strike with its last action, or it has a creature Engulfed.\n* * *\n\n**Effect** The zaramuun attempts to [[Actions/Disarm|Disarm]] one primarily metal or stone object from the Struck or Engulfed creature and casts its innate [[Spells/Planar Tether|Planar Tether]] on the target creature."

  - name: "Sand Glide"
    desc: "  The zaramuun can [[Actions/Burrow|Burrow]] through sand and dirt (but not stone) at its full burrow Speed, leaving no tunnel or sign of its passing. Any Engulfed creatures are left behind when it Burrows. Loose sand and scree are not difficult terrain for a zaramuun."

  - name: "Sandblast"
    desc: "`pf2:2` (earth) The zaramuun sprays a blast of sand that deals 11d10 slashing damage to all creatures in a 60-foot line (DC 38 Reflex check).\n\nIt can't Sandblast again for 1d4 rounds.\n* * *\n\n**Critical Success** No effect.\n\n**Success** Half damage.\n\n**Failure** Full damage.\n\n**Critical Failure** Full damage and [[Conditions/Blinded|Blinded]] for 1 round."
 
```

```encounter-table
name: Zaramuun
creatures:
  - 1: Zaramuun
```



Zaramuuns are beings of elemental sand that hide in deserts and wastelands. They disguise themselves as massive dunes before rising up to attack living creatures. The most infamous zaramuuns kill any living creatures they find, but others simply rob their victims of all metal and stone possessions before fleeing. Although zaramuuns insist they are only reclaiming what was taken from their ancestral earth, this is simple self-delusion; most zaramuuns use their stolen goods as payment and material components to conjure fiends, for Zaramuuns were exiled from the Plane of Earth after worshipping fiends who promised to give them power over other elementals. This worship gradually transformed into servitude, and now many zaramuuns believe that if they send enough souls to their masters, they will be set free.
