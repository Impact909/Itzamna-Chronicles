---
title: "Clockwork Spy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4UPng80qohbBZWSn" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Clockwork Spy"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Clockwork Spy"
level: "Creature -1"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5"
abilityMods: [-1, 3, 0, -5, 2, 0]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +2, __Ref__ +7, __Will__ +4"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 2, orichalcum 2"
abilities_top:
  - name: ""

  - name: "Record Audio"
    desc: "`pf2:1`  The clockwork spy records all sounds within 25 feet onto a small gemstone worth 1 gp embedded in its body. The clockwork spy can record up to 1 hour of sound on a single gemstone. Once it begins recording, it can't cease recording early, nor can it record onto a gemstone that already contains a recording.\n\nSome clockwork spies contain multiple gemstones to allow for a series of recordings. Since clockwork spies are not intelligent, they must be given simple commands regarding when to start recording sounds. A clockwork spy can differentiate between different kinds of creatures but not between specific individuals.\n\nThe spy can start or stop playback of recorded sound by spending a single action. Removing a gemstone from or installing a gemstone into a clockwork spy requires a successful DC 14 Thievery check check to [[Actions/Disable a Device|Disable a Device]]; on a failure, the gemstone is undamaged, but any recorded sounds are erased and the gemstone still can't be used to make another recording."

  - name: "Wind-Up"
    desc: "  24 hours, DC 14 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to [[Actions/Disable a Device|Disable a Device]] to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Self-Destruct"
    desc: "`pf2:r`  A clockwork spy must use this reaction unless specifically programmed otherwise by its creator.\n\n**Trigger** The clockwork spy is reduced to 0 Hit Points.\n* * *\n\n**Effect** The spy thrashes around and emits a tinny scream followed by a steady ticking sound. At the beginning of what would have been its next turn, the clockwork spy explodes, dealing 1d10 piercing damage in a 5-foot radius (DC 16 Reflex check save). Its gemstone is destroyed, along with any information contained inside it.\n\nAn adjacent creature can cancel the self-destruct sequence by succeeding at a DC 16 Thievery check check to [[Actions/Disable a Device|Disable a Device]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spherical Body"
    desc: "+7 (finesse)\n__Damage__  1d6 - 1 bludgeoning"
 
```

```encounter-table
name: Clockwork Spy
creatures:
  - 1: Clockwork Spy
```



Engineers, technologists, and mechanically gifted wizards employ clockwork spies-tiny, spiderlike constructs capable of recording and playing back audio-to surreptitiously surveil their enemies or steal secrets from competitors. Their spindly bodies and delicate components make them unsuitable for combat; in fact, most builders construct clockwork spies with a self-destruct mechanism to ensure the spies' meddling can't be traced back to them.

* * *

Intricate, complex machines, clockworks are built with care by highly skilled engineers. Though their creation involves some amount of magic, they're primarily mechanical, packed with precision-tuned gears and springs working in concert.

The sturdy mainspring within a clockwork must be wound to provide the energy needed to power the device. Some larger clockworks contain a series of springs for different limbs that each need to be wound. A clockwork's crafter creates a unique metal key while building the clockwork; winding the clockwork usually involves inserting the key into the machine's back and turning clockwise. Larger clockworks require greater strength to turn the key, and typically have larger keys to allow for more torque-some even accommodating a team of winders rather than an individual. Programming a clockwork requires both the key and the knowledge to set the program correctly, information usually reserved for the clockwork's creator or owner.
