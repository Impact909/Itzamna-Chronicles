---
title: "Carnivorous Crystal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WfMm7QGRuCOgrwPB" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Carnivorous Crystal"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Carnivorous Crystal"
level: "Creature 11"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[mindless]]
trait_03: [[ooze]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +24"
abilityMods: [7, -5, 5, -5, 0, -5]
speed: 10 feet,  climb 10 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +20, __Ref__ +10, __Will__ +15"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  acid,  critical hits (except bludgeoning or sonic),  precision,  unconscious,  visual,  mental; __Weaknesses__ sonic 10; __Resistances__ piercing 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A carnivorous crystal can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Split"
    desc: "  Whenever the carnivorous crystal takes a critical hit from an attack that deals bludgeoning or sonic damage, or it critically fails its saving throw against an effect that deals bludgeoning or sonic damage, it might split. If the carnivorous crystal has at least 15 HP remaining after taking the damage, it splits into two identical crystals, each with half the original's Hit Points. When the carnivorous crystal splits, one crystal remains in the same space and the other appears in an adjacent unoccupied space. If no adjacent space is unoccupied, the crystal automatically pushes creatures out of the way to fill a space."

  - name: "Subsonic Hum"
    desc: " (auditory,aura,mental) 60 feet. A creature that enters or starts its turn within the aura must succeed at a DC 28 Will check save or become [[Conditions/Stunned|Stunned 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+24 (versatile s)\n__Damage__  4d8 + 7 piercing"

  - name: "Crystallize"
    desc: "`pf2:1` (attack) **Requirements** The crystal has a creature engulfed.\n* * *\n\n**Effect** The engulfed creature must succeed at a DC 28 Fortitude check save or become [[Conditions/Slowed|Slowed 1]] until it is no longer engulfed. If the creature is already slowed, it becomes petrified as it is turned into crystal and expelled by the carnivorous crystal onto the ground.\n\nIn 1d4 hours, the petrified victim shatters and a new carnivorous crystal emerges from the remains."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 28 Reflex check, 2d6 slashing damage, Escape DC 28, Rupture 25 (bludgeoning only).\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Freeze"
    desc: "`pf2:2` (concentrate) Until the next time it acts, the carnivorous crystal appears to be a mundane crystal formation. It has an automatic result of 40 on Deception and Stealth checks and DCs to pass as a crystal formation."

  - name: "Razor Sharp"
    desc: "  If a carnivorous crystal hits with an attack and rolls a natural 19 on the d20 roll, the attack is a critical hit. This has no effect if the 19 would be a failure."
 
```

```encounter-table
name: Carnivorous Crystal
creatures:
  - 1: Carnivorous Crystal
```



Carnivorous crystals are strange ooze creatures native to the Plane of Earth. Unlike most oozes, their bodies are not homogeneously fluid; rather, interspersed within their glassy, viscous resin are thousands of sharp mineral formations that nevertheless possess some of the same flexibility and mobility as the rest of the creature's gooey body.
