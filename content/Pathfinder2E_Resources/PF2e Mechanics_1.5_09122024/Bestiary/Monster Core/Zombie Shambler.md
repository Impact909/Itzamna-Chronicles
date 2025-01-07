---
title: "Zombie Shambler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9qu4xv4kKcVljEna" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Zombie Shambler"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Zombie Shambler"
level: "Creature -1"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[zombie]]
modifier: 0
perception:
  - name: "Perception"
    desc: "+0; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +7"
abilityMods: [3, -2, 2, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +6, __Ref__ +0, __Will__ +2"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed,  mental; __Weaknesses__ vitality 5, slashing 5"
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
    desc: "+7 ()\n__Damage__  1d6 + 3 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 ()\n__Damage__  1d8 + 3 piercing"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zombie Shambler
creatures:
  - 1: Zombie Shambler
```



A zombie shambler is a slow-moving horror dangerous in larger groups.

* * *

A zombie's only desire is to consume the living. Unthinking and ever-shambling harbingers of death, zombies stop only when they're destroyed.
