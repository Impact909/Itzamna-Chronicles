---
title: "Husk Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tncZDhGy3LB4UllM" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Husk Zombie"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Husk Zombie"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[zombie]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Deception: +6, Intimidation: +6, Stealth: +7"
abilityMods: [4, 3, 3, -1, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +9, __Will__ +7"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 5, slashing 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortsword|Shortsword]]"
abilities_mid:
  - name: ""
  - name: "Slow"
    desc: "  A husk zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+11 (agile, versatile s)\n__Damage__  1d6 + 4 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile)\n__Damage__  1d8 + 4 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The husk zombie deals an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Sudden Surge"
    desc: "  **Trigger** The husk zombie's turn begins\n* * *\n\n**Effect** The husk zombie has a sudden burst of speed. They are [[Conditions/Quickened|Quickened]] this turn and can use the extra action only to Stride or Strike. If the husk zombie's first action this turn is a melee Strike, the target is [[Conditions/Off-Guard|Off-Guard]] against the attack.\n\nThe husk zombie can't use Sudden Surge again until after they spend at least 10 minutes standing motionless."
 
```

```encounter-table
name: Husk Zombie
creatures:
  - 1: Husk Zombie
```



Rather than allow a body to rot, some necromancers attempt to dry-cure the corpse to prevent further deterioration. Combined with special reagents, this process can preserve a rudimentary form of intelligence, allowing husk zombies to act more like predators than their mindless kin. Most husk zombies have no memories of their prior lives, though some keep trinkets from that time, oblivious as to why they value such items. A rare few husk zombies retain most of their former knowledge, though they tend to have gaps in their memory.

* * *

Simple to create and varied in purpose, these shambling undead are often used for their strength and endless stamina to conduct boring, repetitive tasks.
