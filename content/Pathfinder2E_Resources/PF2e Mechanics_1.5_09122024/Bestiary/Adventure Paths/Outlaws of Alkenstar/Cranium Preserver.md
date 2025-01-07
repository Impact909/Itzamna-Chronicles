---
title: "Cranium Preserver"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.g6B6UVB06nlpBzNe" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Cranium Preserver"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Cranium Preserver"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[evil]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common; any languages spoken by its preserved heads"
skills:
  - name: "Skills"
    desc: "Occultism: +22, Religion: +22, Lore (any known by its preserved heads): +19"
abilityMods: [7, 0, 3, 5, 0, 0]
speed: 25 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +16, __Will__ +19"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ electricity 10, vitality 10"
abilities_top:
  - name: ""

  - name: "Undead Crafter"
    desc: "  The cranium preserver knows one version of the [[Spells/Create Undead|Create Undead]] ritual for every four heads it has preserved (a typical cranium preserver has 12 preserved heads). The cranium preserver can use its heads to make separate rolls as both the primary and secondary casters of the ritual."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cranium Remover"
    desc: "+23 (deadly d12, sweep)\n__Damage__  3d8 + 9 slashing"

  - name: "**Ranged** `pf2:1` Embalming Fluid"
    desc: "+21 (range 120 feet)\n__Damage__  2d8 + 3 mental 2d8 + 3 void"

  - name: "Rituals"
    desc: "_Create Undead (Mummies, Skeletons, and Zombies)_"

  - name: "Jettison Cranium"
    desc: "`pf2:2` (incapacitation,mental,void) The cranium preserver ejects one of its preserved-head jars at a point within 100 feet. The jar explodes, and all creatures in a 10-foot burst must attempt a DC 28 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d8 mental damage and 2d8 void damage.\n\n**Failure** The creature takes 4d8 mental damage and 4d8 void damage. The discharged mental anguish released from the preserved head causes the creature to become [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The creature takes 8d8 mental and 8d8 void damage. The discharged mental anguish released from the preserved head causes the creature to become confused for 2 rounds."

  - name: "Slosh"
    desc: "  Whenever the cranium preserver ends a Stride, the movement causes necrotic embalming fluid and preserved body parts to slosh about and spill from its central vat. Each creature adjacent to the cranium preserver when it finishes its Stride must attempt a DC 26 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d8 mental damage and 1d8 void damage.\n\n**Failure** The creature takes 2d8 mental damage and 2d8 void damage.\n\n**Critical Failure** The creature takes 4d8 mental and 4d8 void damage. If the creature is alive, the preserved body parts sense the presence of a living creature and cling to it, causing the creature to become [[Conditions/Clumsy|Clumsy 2]] for 1 round."
 
```

```encounter-table
name: Cranium Preserver
creatures:
  - 1: Cranium Preserver
```



Cranium preservers serve necromancers as walking laboratories for undead. A typical cranium preserver has a metallic and spider-like body, which holds aloft a large central glass vat surrounded by a dozen or more smaller, head-sized glass vats. Each vat is filled with a special embalming fluid that can preserve the minds of slain enemies.
