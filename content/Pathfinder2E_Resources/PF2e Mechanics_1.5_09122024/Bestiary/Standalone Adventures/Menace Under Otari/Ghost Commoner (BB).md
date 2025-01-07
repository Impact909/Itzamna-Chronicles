---
title: "Ghost Commoner (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oHoflvFHqTzdwUbz" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Ghost Commoner (BB)"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Ghost Commoner (BB)"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +12"
abilityMods: [-5, 3, 0, 0, 2, 2]
speed:  fly 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +11, __Will__ +8"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, rejuvenation; __Immunities__  poison,  unconscious,  bleed,  precision; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  A ghost can stray no more than 120 feet from where it was killed or the place it haunts. Some are bound to items or creatures that were special to them rather than a location."

abilities_mid:
  - name: ""
  - name: "Incorporeal"
    desc: "  A ghost has no body and can pass through physical objects, though it can't end its turn inside one. Most checks that use Strength and require a body, such as [[Actions/Grapple|Grapple]] and [[Actions/Shove|Shove]], don't work against a ghost, and a ghost can't attempt such checks."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Setting right the injustice that led to the ghost's death allows it to move on to the afterlife. Otherwise, when destroyed, the ghost re-forms after 2d4 days within the location it's bound to, fully healed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+13 (agile, finesse, magical)\n__Damage__  2d6 + 2 void"

  - name: "[[Creature Family Ability Glossary/(Ghost) Frightful Moan|Frightful Moan]]"
    desc: "`pf2:2` (divine,fear,mental) Each living creature within 30 feet who hears the ghost must attempt a DC 21 Will check save. On a failure, a creature gains the [[Conditions/Frightened|Frightened 2]] condition (or [[Conditions/Frightened|Frightened 3]] on a critical failure).\n\nOn a success, a creature can't be affected by this ghost's Frightful Moan for 1 minute."
 
```

```encounter-table
name: Ghost Commoner (BB)
creatures:
  - 1: Ghost Commoner (BB)
```




