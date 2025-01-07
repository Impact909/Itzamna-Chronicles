---
title: "Giant Wasp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zsYZL4zzZtElcHj3" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Giant Wasp"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Wasp"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +9"
abilityMods: [4, 4, 4, -5, 1, 1]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +9, __Ref__ +11, __Will__ +6"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+12 (poison)\n__Damage__  1d12 + 4 piercing plus giant-wasp-venom"

  - name: "Giant Wasp Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 19 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** no effect (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "Implant Eggs"
    desc: "`pf2:1`  The giant wasp lays eggs in an adjacent creature that is [[Conditions/Paralyzed|Paralyzed]] or [[Conditions/Unconscious|Unconscious]], exposing it to the wasp larva disease."

  - name: "Wasp Larva"
    desc: " (disease) **Saving Throw** DC 21 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1d6 days)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1d3 days)\n\n**Stage 3** 5d6 damage, larva emerges (disease ends)"
 
```

```encounter-table
name: Giant Wasp
creatures:
  - 1: Giant Wasp
```



Giant wasps are much more dangerous but less common than their smaller kin, and—to the relief of those who encounter them—they tend to be solitary.

* * *

While the common wasp poses little threat to a hardy adventurer aside from an uncomfortable sting, a large and aggressive swarm of these territorial insects—to say nothing of their oversized kin—can lay low an entire party of heroes. The wasps represented here are of the common variety, also known as yellow jackets, but many other sorts of dangerous wasps exist, such as a Garundi variant that swarms in such great numbers that it can decimate entire villages.
