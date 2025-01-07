---
title: "Gelatinous Cube"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fm9kpY65e7vk9kEV" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Gelatinous Cube"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Gelatinous Cube"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11"
abilityMods: [4, -5, 5, -5, 0, -5]
speed: 15 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +12, __Ref__ +0, __Will__ +5"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  mental; __Resistances__ electricity 5"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A gelatinous cube can sense nearby motion through vibration and air movement."

  - name: "Transparent"
    desc: "  A gelatinous cube is so clear that it's difficult to spot. A successful DC 23 Perception check check is required to notice a stationary cube, and a creature must be [[Actions/Search|Searching]] to attempt this check.\n\nA creature that walks into the cube is automatically Engulfed (this usually causes the GM to call for initiative)."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cube Face"
    desc: "+11 ()\n__Damage__  1d6 acid plus paralysis"

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 19 Reflex check, 2d6 acid, Escape DC 19, Rupture 7\n\nA creature Engulfed by the gelatinous cube must also attempt a saving throw against paralysis.\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Paralysis"
    desc: " (incapacitation) A creature Engulfed by the cube or hit by its attack is [[Conditions/Paralyzed|Paralyzed]] unless it succeeds at a DC 20 Fortitude check save. A victim can attempt a new save to recover at the end of each of its turn."

  - name: "Weak Acid"
    desc: "  A gelatinous cube's acid damages only organic material-not metal, stone, or other inorganic substances."
 
```

```encounter-table
name: Gelatinous Cube
creatures:
  - 1: Gelatinous Cube
```



Found underground or in dungeons, these quivering cubes of slime continuously scour their domain for food. The acid in their bodies is weak enough that many gelatinous cubes still contain the gear of their victims, as they're unable to break them down.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
