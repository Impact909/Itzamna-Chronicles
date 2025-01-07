---
title: "Rust Monster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iu2sBd0qYtoU48jO" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Rust Monster"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Rust Monster"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +7"
abilityMods: [0, 3, 1, -4, 1, 0]
speed: 35 feet,  climb 10 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +10, __Will__ +6"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40"
abilities_top:
  - name: ""

  - name: "Metal Scent 30 feet"
    desc: "  A rust monster can smell metal as a precise sense."

abilities_mid:
  - name: ""
  - name: "Tail Trip"
    desc: "`pf2:r`  **Trigger** A creature carrying a metal item attempts to move out of a square within reach of the rust monster's tail.\n* * *\n\n**Effect** The rust monster makes a tail Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Antenna"
    desc: "+10 (finesse)\n__Damage__ "

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+8 (finesse)\n__Damage__  1d10 + 4 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+8 (finesse)\n__Damage__  1d4 + 2 bludgeoning plus improved-knockdown"

  - name: "Antenna Disarm"
    desc: "`pf2:1`  The rust monster attempts to [[Action Macros/Disarm_ Athletics|Disarm]] a metal item a creature is holding using its antenna (with the same modifier as an antenna Strike).\n\nOn a success, the item is subject to the rust monster's rust ability in addition to the effects of the Disarm, and if the check to Disarm is a critical success, the rust monster drops the item on the ground in its own space."

  - name: "Rust"
    desc: "  A rust monster's antenna causes metal to rapidly rust and corrode.\n\nIf it succeeds at an antenna Strike or Disarm attempt with its antenna, the rust monster deals 2d6 damage (doubled on a critical hit) to a metal item the target is wearing or holding, ignoring its Hardness.\n\nIf the rust monster hits an unattended metal item, the item takes this damage automatically.\n\nIf a creature uses the [[Feats/Shield Block|Shield Block]] reaction with a metal shield against an antenna attack, the shield is automatically broken, but no other item is rusted on that attack."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Rust Monster
creatures:
  - 1: Rust Monster
```



Found in lost dungeons, deep caves, and abandoned mines, rust monsters are a bane to any adventurers who rely on armor, weapons, or other metal items. These strange-looking creatures grow to about 5 feet long, with four insectile legs and a long tail ending in a four-pronged appendage resembling a tiny windmill. However, it is the rust monster's feathery antennae that strike fear in the hearts of battle-hardened warriors, for a single touch from even just one antenna can reduce an adventurer's most valuable tools to a useless pile of rust.

Rust monsters aren't inherently aggressive creatures, but they're voracious oxidivores, meaning they consume the rust created by their antennae. The creatures savagely attack anything that gets between them and a possible meal, and they relentlessly pursue any source of metal. A rust monster can be distracted by a single metal-rich item, but they are often encountered in groups of three or more, sharply raising the cost of escape.

Rust monsters are a terrible scourge in mining communities. If a group of rust monsters discovers rich veins of ore, they can multiply quickly. By weakening tunnels, attacking workers, and consuming the source of the miners' livelihood, these aberrations have created many mountainside ghost towns.
