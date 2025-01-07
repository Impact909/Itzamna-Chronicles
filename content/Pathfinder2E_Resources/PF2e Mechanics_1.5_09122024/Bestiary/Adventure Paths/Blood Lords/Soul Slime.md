---
title: "Soul Slime"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JTuN670YY4BuUp1r" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Soul Slime"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Soul Slime"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Lifesense 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +35"
abilityMods: [9, -3, 6, -5, 0, -5]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +33, __Ref__ +24, __Will__ +27"
hp: 420
health:
  - name: ""
  - name: HP
    desc: "420; __Immunities__  acid,  critical hits,  void,  piercing,  vitality,  precision,  slashing,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+35 (reach 10 feet)\n__Damage__  3d10 + 15 bludgeoning plus siphon-soul"

  - name: "**Ranged** `pf2:1` Ooze Globule"
    desc: "+28 (range increment 60 feet)\n__Damage__  2d10 + 15 bludgeoning plus siphon-soul"

  - name: "Disgorge Soul"
    desc: "`pf2:r`  **Trigger** The soul slime takes physical damage\n* * *\n\n**Effect** The impact causes the soul slime to release a burst of semi-digested soul fragments. The soul slime becomes [[Conditions/Concealed|Concealed]] until the beginning of its next turn. The soul slime can't use this concealment to Hide or [[Actions/Sneak|Sneak]]."

  - name: "Disturbing Wail"
    desc: "`pf2:2` (auditory,mental) **Requirements** The soul slime is using Soul Facsimile to adopt a creature's form\n* * *\n\n**Effect** The soul slime releases an incoherent wail composed of countless overlapping noises made by the creatures whose souls it has siphoned. This disturbing cacophony deals 6d10 mental damage and 6d10 sonic damage to each creature in a 30-foot-radius burst centered on the soul slime (DC 37 Will check). On a failed save, a creature is additionally [[Conditions/Stunned|Stunned 2]]. The soul slime can't use Disturbing Wail again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 40 Reflex check, 5d10 bludgeoning damage, Escape DC 40, Rupture 20\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Siphon Soul"
    desc: "  A soul slime's touch siphons away portions of a creature's soul. Its Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 3d6 void damage to living creatures and 3d6 vitality damage to undead and other creatures with void healing."

  - name: "Soul Facsimile"
    desc: "`pf2:1` (occult) The soul slime assumes the shape and features of any Large, Medium, or Small creature whose soul the soul slime has siphoned for up to 1 minute. This doesn't change the soul slime's statistics, only its outward appearance. While transformed in this way, the soul slime can revert to its natural shape as a single action, and the soul slime automatically reverts to its natural shape when it takes physical damage."
 
```

```encounter-table
name: Soul Slime
creatures:
  - 1: Soul Slime
```



Soul slimes are swirling, blue-gray masses of protoplasm that feed on the quintessence contained within souls. Typically, soul slimes acquire this quintessence by consuming the living, the undead, or souls imprisoned in other objects, although soul slimes can also feed on the quintessence of the Outer Planes and their occupants. Soul slimes digest these siphoned souls over decades. As long as a portion of a soul remains undigested, a soul slime can adopt the shape and use the vocalizations of that soul—a tactic soul slimes routinely adopt to get close to their prey while hunting. As soul slimes lack the intelligence to truly impersonate or mimic the souls they digest, they are obvious facsimiles and are entirely incapable of speech.
