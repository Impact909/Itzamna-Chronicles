---
title: "Pufferfish"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BhAnHdqceoRlihXP" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Pufferfish"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Pufferfish"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +2, Athletics: +4"
abilityMods: [2, 0, 2, -5, 1, -2]
speed:  swim 15 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +5, __Ref__ +3, __Will__ +2"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Toxic Body"
    desc: "  Anyone who hits a pufferfish with a melee unarmed attack or a non-reach melee weapon must succeed at a DC 13 Reflex check save or be pierced by a spine, taking 1 piercing damage and being exposed to pufferfish venom."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+6 ()\n__Damage__  1d6 + 1 piercing plus pufferfish-venom"

  - name: "Inflating Rush"
    desc: "`pf2:2`  The pufferfish Swims up to its Speed and then inflates. Each creature within 5 feet of its space at the end of its movement must succeed at a DC 13 Reflex check save or take 1 piercing damage and be exposed to pufferfish venom."

  - name: "Pufferfish Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Maximum Duration** 24 hours\n\n**Stage 1** 1d4 poison damage (1 round)\n\n**Stage 2** 1d4 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** 1d4 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)\n\n**Stage 4** 1d4 poison damage and paralyzed for 2d10 hours (1 round)"
 
```

```encounter-table
name: Pufferfish
creatures:
  - 1: Pufferfish
```



The pufferfish defends itself by filling its flexible body with air or water to extend a number of spikes that otherwise lie flat against its skin. While normally quite slow and deliberate, the pufferfish can contort its body to gain a sudden burst of speed that can catch predators off guard.

* * *

Swimming in vast shoals through open ocean underneath the sparkling sun, lurking deep in the muddy beds of rivers, or schooling in pristine lakes, fish are found nearly anywhere there is water.
