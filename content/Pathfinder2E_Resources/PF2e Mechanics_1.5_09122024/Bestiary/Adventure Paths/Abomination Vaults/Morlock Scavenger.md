---
title: "Morlock Scavenger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TLU7a6lRdtEc6AvX" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/morlock
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Morlock Scavenger"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Morlock Scavenger"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[morlock]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +5, Stealth: +7"
abilityMods: [2, 4, 1, -2, 3, 1]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +4, __Ref__ +9, __Will__ +6; +2 status to all saves vs. disease and poison"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]]"
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+9 (agile, finesse, versatile s)\n__Damage__  1d4 + 2 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 (agile)\n__Damage__  1d4 + 2 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+9 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 2 piercing"

  - name: "Scuttling Attack"
    desc: "`pf2:2`  The morlock scavenger Strides twice, ignoring difficult terrain caused by natural cavern features like rubble or stalagmites. At any point during its movement, the morlock can make a melee Strike against an enemy in its reach."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The morlock deals an extra 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Swarming Stance"
    desc: "  A morlock can share the same space as another morlock, but no more than two morlocks can occupy the same space. When morlocks share the same space, they gain a +1 circumstance bonus to attack rolls."
 
```

```encounter-table
name: Morlock Scavenger
creatures:
  - 1: Morlock Scavenger
```



The morlock scavenger is a lankier, smaller version of a typical morlock. Their stature allows them to wriggle into areas other morlocks can't access.

* * *

Morlocks originate from humans long lost to the surface world. They have an affinity for machinery, scavenging, and strange occult behaviors.
