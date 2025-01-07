---
title: "Stony Goat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RNXbI608T57QsWhU" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Stony Goat"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Stony Goat"
level: "Creature 2"
rare_03: [[Rare]]
alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +8, Survival: +6"
abilityMods: [3, 4, 3, -4, 2, 1]
speed: 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +11, __Will__ +5"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Cud"
  - name: "Cliff Climber"
    desc: "  A stony goat can trot across the steepest cliffs. It doesn't need to attempt [[Actions/Climb|Climb]] checks to scale inclines, and it isn't [[Conditions/Off-Guard|Off-Guard]] while Climbing an incline. It ignores difficult terrain caused by rocks, rubble, and uneven ground made of earth and stone."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Self-Petrify"
    desc: "`pf2:r` (polymorph) **Trigger** The stony goat gains the [[Conditions/Frightened|Frightened]] condition or takes more than 8 damage in a single hit\n* * *\n\n**Effect** The stony goat turns to stone in self-defense. It gains the [[Conditions/Petrified|Petrified]] condition for 1d4 rounds. If the goat is damaged while it's petrified, it immediately heals by that amount by absorbing minerals from its cud, causing its cud to lose value equal to the amount of Hit Points restored (for instance, losing 5 gp worth of value to restore 5 Hit Points); if the goat's cud is reduced to 0 gp, it has the minerals fully drained from it, and the goat won't form more cud until it has eaten a sufficient quantity of rock and slept."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Head"
    desc: "+8 ()\n__Damage__  1d8 + 3 bludgeoning"

  - name: "Overhead Leap"
    desc: "`pf2:1` (move) The stony goat [[Actions/Leap|Leaps]] up to 12 feet vertically and 20 feet horizontally; this movement doesn't trigger reactions."

  - name: "Shove and Run"
    desc: "`pf2:1`  The stony goat attempts to [[Actions/Shove|Shove]] the nearest creature and then Strides with a +20-foot circumstance bonus to Speed."

  - name: "Stone Bolt"
    desc: "`pf2:r`  **Trigger** The stony goat loses the [[Conditions/Petrified|Petrified]] condition\n* * *\n\n**Effect** The stony goat's first instinct is to escape. It Strides with a +20 circumstance bonus to its Speed."
 
```

```encounter-table
name: Stony Goat
creatures:
  - 1: Stony Goat
```




