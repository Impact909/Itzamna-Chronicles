---
title: "Zombie Brute"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.opR8nbsAXfqUYHy1" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Zombie Brute"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Zombie Brute"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[zombie]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11"
abilityMods: [5, -3, 4, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +10, __Ref__ +3, __Will__ +6"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (reach 10 feet)\n__Damage__  1d12 + 5 bludgeoning plus improved-push"

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Zombie Brute
creatures:
  - 1: Zombie Brute
```



Necromantic augmentations have granted this zombie increased size and power.

* * *

A zombie's only desire is to consume the living. Unthinking and ever-shambling harbingers of death, zombies stop only when they're destroyed.
