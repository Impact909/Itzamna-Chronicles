---
title: "Ice Golem"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5B8FA7aNXVdAP9M1" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/construct
  - pf2e/creature/type/golem
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Ice Golem"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Ice Golem"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[cold]]
trait_02: [[construct]]
trait_03: [[golem]]
trait_04: [[mindless]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [5, 0, 4, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +11, __Will__ +9"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  cold,  electricity,  magic,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Resistances__ physical 5 (except adamantine or bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Golem Antimagic"
    desc: "  harmed by fire (4d6, 1d10 from areas or persistent damage); healed by cold (area 1d6 HP); slowed by water\n* * *\n\nA golem is immune to spells and magical abilities other than its own, but each type of golem is affected by a few types of magic in special ways. If an entry lists multiple types (such as \"cold and water\"), either type of spell can affect the golem.\n\n**Harmed By** Any magic of this type that targets the golem causes it to take the listed amount of damage (this damage has no type) instead of the usual effect. If the golem starts its turn in an area of magic of this type or is affected by a persistent effect of the appropriate type, it takes the damage listed in the parenthetical.\n\n**Healed By** Any magic of this type that targets the golem makes the golem lose the slowed condition and gain HP equal to half the damage the spell would have dealt. If the golem starts its turn in an area of this type of magic, it gains the HP listed in the parenthetical.\n\n**Slowed By** Any magic of this type that targets the golem causes it to be [[Conditions/Slowed|Slowed 1]] for 2d6 rounds instead of the usual effect. If the golem starts its turn in an area of this type of magic, it's [[Conditions/Slowed|Slowed 1]] for that round.\n\n**Vulnerable To** Each golem is vulnerable to one or more specific spells, with the effects described in its stat block."

  - name: "Icy Demise"
    desc: " (arcane,cold) When an ice golem is destroyed, its body explodes in a blast of frigid air and razor-sharp ice, dealing 2d6 slashing damage and 2d6 cold damage to creatures in a 20-foot emanation, with a DC 19 Reflex check save."

  - name: "Vulnerable to Endure Elements"
    desc: "  An ice golem can be targeted with [[Spells/Environmental Endurance|Environmental Endurance]] even if it's not willing. If it is targeted, for 1 round it can't use Breath Weapon or benefit from creeping cold, and its fist attack doesn't deal cold damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+15 (magical, versatile p)\n__Damage__  2d6 + 7 bludgeoning 1d6 cold"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,cold) The ice golem exhales a blast of freezing mist that deals 6d6 cold damage in a 30-foot cone (DC 22 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Creeping Cold"
    desc: " (arcane,cold) When the ice golem gets a critical hit with a fist Strike, the target also takes 2d6 persistent cold damage and is [[Conditions/Slowed|Slowed 1]] for 1 round."
 
```

```encounter-table
name: Ice Golem
creatures:
  - 1: Ice Golem
```



Ice golems are either carved from massive blocks of ice, or pieced together from individual components that are then fused together through heat and refreezing. In most cases, the resulting shape is little more than a crude approximation of a humanoid form, but given the right talent, an ice golem could be an exquisitely carved statue of a mythical creature, famous persona, or even a deity.

While ice golems most frequently serve as guardians in freezing climates, the magic that holds an ice golem together keeps it from melting in warmer temperatures. This, combined with the fact that ice golems lie on the lower end of the scale as far as cost and difficulty to create, gives these constructs unusual features that puts them in great demand. The rich and powerful in hot, arid regions often commission ice golems not only as guardians for their estates and vaults, but for comfort-the presence of an ice golem standing quietly sentinel in the corner of a room can help to keep the chamber at a comfortable temperature. The truly decadent use ice golems as servants to keep drinks cold.
