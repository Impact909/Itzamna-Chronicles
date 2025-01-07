---
title: "Clockwork Clock Tower"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sc9vxTUGCYAIUFX1" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Clockwork Clock Tower"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Clockwork Clock Tower"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +38"
abilityMods: [10, 6, 7, -5, 6, -5]
speed: 40 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +36, __Ref__ +33, __Will__ +31"
hp: 325
health:
  - name: ""
  - name: HP
    desc: "325; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 20, orichalcum 20; __Resistances__ physical 20 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  1 week DC 40 Thievery check\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Doleful Tolling"
    desc: "`pf2:0` (arcane,auditory,incapacitation) **Trigger** The clockwork clock tower rolls initiative\n* * *\n\n**Effect** The clock tower chimes, and all non-clockwork creatures within 300 feet who can hear it must succeed at a DC 42 Will check save or be [[Conditions/Slowed|Slowed 1]] for 1 round ([[Conditions/Slowed|Slowed 2]] on a critical failure)."

  - name: "Durable Exterior"
    desc: "  When a clockwork clock tower is reduced to fewer than 200 HP or is damaged by a critical hit, its exterior shatters to reveal internal mechanisms, reducing its AC to 44 until it recovers enough HP to reach 200 HP or more."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+36 (reach 30 feet)\n__Damage__  4d12 + 18 bludgeoning plus stutter-time"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+36 (agile, reach 20 feet)\n__Damage__  4d8 + 18 bludgeoning"

  - name: "Overclock"
    desc: "`pf2:1`  The clockwork clock tower loses 1 day from its winding time and becomes [[Conditions/Quickened|Quickened]] for 3 rounds. It can use this extra action to Step, Stride, or Strike. This quickened condition ends immediately if the clock tower is damaged by orichalcum."

  - name: "Stutter Time"
    desc: " (arcane,incapacitation) A creature struck by a clockwork clock tower's fist must make a DC 40 Will check save as time flows unevenly around it.\n* * *\n\n**Critical Success** The creature is [[Conditions/Quickened|Quickened]] for 1 round and can use this extra action to Step, Stride, or Strike.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 3]].\n\n**Critical Failure** The creature is knocked out of time, which ceases to flow around the creature for 1 round. It is invulnerable to all damage, it can't be targeted or affected by anything, and no rounds elapse for any timed durations, conditions, afflictions, and other effects it has. The target can't act and remains fixed in place, defying gravity if applicable. After time begins to flow again for it, the creature is stunned 3."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 42 Reflex check save\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Clockwork Clock Tower
creatures:
  - 1: Clockwork Clock Tower
```



Clockworks are machines built by engineers and augmented with magic. A clock tower reconfigured as an animated clockwork can rotate slices of time.
