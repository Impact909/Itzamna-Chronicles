---
title: "Spear Frog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HhvaEzM5wxeVLpbO" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Spear Frog"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Spear Frog"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[animal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +0"
abilityMods: [-2, 3, 1, -4, 2, 0]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +5, __Ref__ +7, __Will__ +6"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Toxic Skin"
    desc: "  Anytime a creature touches the spear frog or an adjacent creature Strikes the spear frog with a melee attack, that creature is exposed to spear frog venom."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 (agile, finesse)\n__Damage__  1d6 piercing plus spear-frog-venom"

  - name: "Spear Frog Venom"
    desc: " (poison) **Saving Throw** DC 15 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)"

  - name: "Sticky Feet"
    desc: "  Spear frogs are not off-guard when [[Actions/Balance|Balancing]] on a narrow surface, and they gain a +4 bonus to Reflex saves to avoid falling."
 
```

```encounter-table
name: Spear Frog
creatures:
  - 1: Spear Frog
```



The spear frog is named for its toxin, which is traditionally used to envenom thrown projectiles like spears and daggers.
