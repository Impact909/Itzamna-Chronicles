---
title: "Clockwork Dragon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VKaMvZx2CqA1DvgZ" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Clockwork Dragon"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Clockwork Dragon"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +33"
abilityMods: [9, 5, 5, -5, 4, -5]
speed: 40 feet,  fly 120 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +28, __Will__ +25"
hp: 265
health:
  - name: ""
  - name: HP
    desc: "265; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 15, orichalcum 15; __Resistances__ physical 15 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "Wind-Up"
    desc: "  1 week, DC 35 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to [[Actions/Disable a Device|Disable a Device]] to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Self-Destruct"
    desc: "`pf2:r`  A clockwork dragon must use this reaction unless specifically programmed otherwise by its creator.\n\n**Trigger** The clockwork dragon is reduced to 0 Hit Points.\n* * *\n\n**Effect** The dragon screeches to a stop and emits a steady, loud ticking sound. At the beginning of what would have been its next turn, the dragon explodes, dealing 12d10 piercing damage in a 40-foot emanation (DC 37 Reflex check save).\n\nAn adjacent creature can cancel the self-destruct sequence by succeeding at a DC 37 Thievery check check to [[Actions/Disable a Device|Disable a Device]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Adamantine Jaws"
    desc: "+33 (adamantine, reach 15 feet)\n__Damage__  3d12 + 17 piercing"

  - name: "**Melee** `pf2:1` Adamantine Claw"
    desc: "+33 (adamantine, agile, reach 10 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+31 (reach 20 feet)\n__Damage__  3d12 + 15 bludgeoning"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+31 (agile, reach 15 feet)\n__Damage__  2d10 + 15 piercing"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The clockwork dragon breathes a spray of flaming oil that deals 16d6 fire damage in a 40-foot cone (DC 37 Reflex check save).\n\nCreatures that fail their saves are covered in burning oil and take 2d6 persistent fire.\n\nThe clockwork dragon can't use Breath Weapon again for 2 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The clockwork dragon makes two claw Strikes and one wing Strike in any order."

  - name: "Spearing Tail"
    desc: "`pf2:2`  The clockwork dragon attacks with the sharp point of its tail.\n\nIt makes a tail Strike against each creature in a 20-foot line, rolling the attack roll once and applying the result to each target. Any creature hit takes 4d6 bleed (8d6 bleed on a critical hit). This counts as two attacks for the dragon's multiple attack penalty."
 
```

```encounter-table
name: Clockwork Dragon
creatures:
  - 1: Clockwork Dragon
```



Clockwork dragons are a marvel of clockwork design. These powerful masterpieces have the ability to fly, making them versatile and dangerous killers. A clockwork dragon's winding mechanism is more efficient than those of other clockworks, allowing it to partially reuse energy generated by flapping its wings. Creating a clockwork dragon requires not only an advanced understanding of clockwork design, but also a greater cache of rare resources, as its body requires solid reinforcement. As a result, most clockwork dragons have adamantine fortification. Creating a clockwork dragon without adamantine is entirely possible, though such dragons are typically smaller and more fragile.

* * *

Intricate, complex machines, clockworks are built with care by highly skilled engineers. Though their creation involves some amount of magic, they're primarily mechanical, packed with precision-tuned gears and springs working in concert.

The sturdy mainspring within a clockwork must be wound to provide the energy needed to power the device. Some larger clockworks contain a series of springs for different limbs that each need to be wound. A clockwork's crafter creates a unique metal key while building the clockwork; winding the clockwork usually involves inserting the key into the machine's back and turning clockwise. Larger clockworks require greater strength to turn the key, and typically have larger keys to allow for more torque-some even accommodating a team of winders rather than an individual. Programming a clockwork requires both the key and the knowledge to set the program correctly, information usually reserved for the clockwork's creator or owner.
