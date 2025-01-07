---
title: "Creeping Cone Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8KCA7g8QldjdpT1r" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/mutant
  - pf2e/creature/type/plant
  - pf2e/creature/type/swarm
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Creeping Cone Swarm"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Creeping Cone Swarm"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[mutant]]
trait_03: [[plant]]
trait_04: [[swarm]]
trait_05: [[wood]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +22"
abilityMods: [6, 5, 6, -4, 2, -1]
speed: 25 feet,  climb 20 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +22, __Ref__ +19, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  acid,  poison,  swarm mind,  precision,  grabbed,  prone,  restrained; __Weaknesses__ area damage 7, axe vulnerability 10, fire 10, splash damage 7; __Resistances__ bludgeoning 10, piercing 10, slashing 7 (except axes)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Blight Burst"
    desc: "`pf2:0` (acid,primal) **Trigger** The creeping cone swarm is reduced to fewer than half its Hit Points or is reduced to 0 Hit Points\n* * *\n\n**Effect** A 15-foot emanation of acid explodes from the creeping cone swarm. Creatures in the area take 3d12 acid damage (DC 25 Reflex check save). Non-blight bonded creatures damaged by this effect are exposed to Ayrzul's Blight."

attacks:
  - name: ""

  - name: "Jagged Scales"
    desc: "`pf2:2` (primal) The creeping cones shake off a barrage of jagged, stony scales. Each creature in a 10-foot burst within 30 feet of the swarm takes 2d12+7 slashing damage (DC 29 Reflex check save)."

  - name: "Pummeling Lurches"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 6d6 bludgeoning damage (DC 29 Fortitude check save). A creature that fails its save falls [[Conditions/Prone|Prone]]."

  - name: "Putrid Spores"
    desc: " (aura,poison,primal) 30 feet.\n\nA creature entering the aura must succeed at a DC 26 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] until the end of its turn ([[Conditions/Sickened|Sickened 2]] on a critical failure).\n\nWhile within the aura, an affected creature takes a –2 circumstance penalty to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute."
 
```

```encounter-table
name: Creeping Cone Swarm
creatures:
  - 1: Creeping Cone Swarm
```



Caustic fluid seeps out from the scales of these sluglike cones, which spawn in unsuspecting hosts until they're mature enough to seek a place to root. Moving in writhing swarms that seek a habitat flush with prey, creeping cones spread Ayrzul's Blight when destroyed, but leaving them to grow unchecked poses a great risk to other creatures.

* * *

The Plane of Wood contains many unique ecosystems formed around species of wondrous trees; when Ayrzul's Blight mutates one of these trees rather than killing it, it can have a cascading effect on the tree's biome. Multiple species often mutate in tandem, becoming warped mockeries and a vector for Ayrzul's Blight. These "blight bonded" creature families are parasites and predators and typically form twisted symbiotic relationships.
