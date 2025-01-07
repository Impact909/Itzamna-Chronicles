---
title: "Kobold Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3C7ZwGzj1p9kPTmx" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/kobold
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Kobold Warrior"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Kobold Warrior"
level: "Creature -1"

alignment: ""
size: "Small"
trait_01: [[humanoid]]
trait_02: [[kobold]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; Darkvision"
languages: "Common, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Crafting: +2, Stealth: +5"
abilityMods: [1, 3, -1, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +3, __Ref__ +7, __Will__ +3"
hp: 7
health:
  - name: ""
  - name: HP
    desc: "7"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Sling|Sling]], [[Equipment/Spear|Spear]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Sling Bullets|Sling Bullets]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spear"
    desc: "+3 ()\n__Damage__  1d6 + 1 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+5 (thrown 20 ft.)\n__Damage__  1d6 + 1 piercing"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+5 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d4 bludgeoning"

  - name: "Scamper"
    desc: "`pf2:1`  **Requirements** The kobold warrior is adjacent to at least one enemy\n* * *\n\n**Effect** The kobold warrior Strides up to their Speed plus 5 feet and gains a +2 circumstance bonus to AC against reactions triggered by this movement. They must end this movement in a space that's not adjacent to any enemy."

  - name: "Sneak Attack"
    desc: "  The kobold warrior deals an extra 1d4 precision damage to off-guard creatures."
 
```

```encounter-table
name: Kobold Warrior
creatures:
  - 1: Kobold Warrior
```



The typical kobold trains in tunnel fighting, learning to use simple weapons that are effective in narrow spaces. Kobolds are capable of landing sneaky strikes against unsuspecting foes, but are just as quick to scamper off to safety when they don't outnumber their enemies by at least two to one.

* * *

Kobolds are small reptilian humanoids. They lurk in dark spaces, usually tunnels and mines beneath the earth, in either warrens of their own design or complexes discovered and colonized after the original builders have moved on. Though kobolds are far more pragmatic than courageous, they use every inch of their cunning to even the playing field between themselves and other, stronger creatures. They attack from the darkness and at range, and kobold artificers and engineers master the art of simple but effective traps, which they use to protect their lairs. Kobolds are skilled at working together by necessity, and they often set up ambushes or hit-and-run assaults that allow them to do the most damage possible without being harmed in return.

Kobolds are diligent and hardworking creatures. While some kobolds live in communal collectives that maintain neutral relations with the creatures around them, they can be easily swayed into serving malevolent powers or megalomaniacal leaders. This is in part due to kobolds' innate pragmatism, as they would rather concede to servitude than risk being killed, but it is also in part due to a reverence for the power they generally lack. Notably, kobold eggs left in the proximity of magical creatures or places tend to absorb similar traits from the exposure. The resulting physical changes mark the appearance of each tribe, but a few lucky kobolds are also born with magical power that reflects their tribe's patron.
