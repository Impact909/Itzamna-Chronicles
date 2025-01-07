---
title: "Kobold Scout"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.stxdhhfroBzyeL1b" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Kobold Scout"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Kobold Scout"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[humanoid]]
trait_02: [[kobold]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Crafting: +3, Nature: +6, Stealth: +7, Survival: +6"
abilityMods: [0, 4, 1, 0, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +9, __Will__ +6; +1 circumstance to all defenses vs. traps"
hp: 16
health:
  - name: ""
  - name: HP
    desc: "16"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+9 (agile, finesse, versatile s)\n__Damage__  1d6 piercing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+9 (range increment 120 feet, reload 1)\n__Damage__  1d8 piercing"

  - name: "Construct Trap"
    desc: "`pf2:3` (manipulate) The kobold scout creates a rudimentary trap on any square adjacent to it. This must be on a surface, such as a floor, wall, or ceiling. The trap activates the next time a creature moves adjacent to it.\n\nThe creature takes 1d6 piercing damage and 1 persistent bleed damage with a DC 16 Reflex check save. The trap is destroyed when activated or after 1 hour, whichever comes first.\n\nThe scout typically carries enough raw materials to make one trap."

  - name: "Scamper"
    desc: "`pf2:1`  **Requirements** The kobold scout is adjacent to at least one enemy.\n* * *\n\n**Effect** The kobold scout Strides up to its Speed plus 5 feet and gains a +2 circumstance bonus to AC against reactions triggered by this movement. It must end this movement in a space that's not adjacent to any enemy."

  - name: "Sneak Attack"
    desc: "  The kobold scout deals an extra 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Kobold Scout
creatures:
  - 1: Kobold Scout
```



Most kobolds encountered outside of a well-defended warren or lair are kobold scouts, those trained for stalking and hunting. They're also often in the thick of the fighting when a warren is invaded, buying time for their comrades to set up various traps and deadfalls.

* * *

Kobolds are small reptilian humanoids. They lurk in dark spaces, usually tunnels and mines beneath the earth, in either warrens of their own design or complexes discovered and colonized after the original builders have moved on. Though kobolds are far more pragmatic than courageous, they use every inch of their cunning to even the playing field between themselves and other, stronger creatures. They attack from the darkness and at range, and kobold artificers and engineers master the art of simple but effective traps, which they use to protect their lairs. Kobolds are skilled at working together by necessity, and they often set up ambushes or hit-and-run assaults that allow them to do the most damage possible without being harmed in return.

Kobolds are diligent and hardworking creatures. While some kobolds live in communal collectives that maintain neutral relations with the creatures around them, they can be easily swayed into serving malevolent powers or megalomaniacal leaders. This is in part due to kobolds' innate pragmatism, as they would rather concede to servitude than risk being killed, but it is also in part due to a reverence for the power they generally lack. Notably, kobold eggs left in the proximity of magical creatures or places tend to absorb similar traits from the exposure. The resulting physical changes mark the appearance of each tribe, but a few lucky kobolds are also born with magical power that reflects their tribe's patron.
