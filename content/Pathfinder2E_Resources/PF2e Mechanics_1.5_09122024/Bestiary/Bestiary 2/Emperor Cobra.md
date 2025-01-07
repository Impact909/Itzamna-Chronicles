---
title: "Emperor Cobra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VK2Pw8GreQcLhN6b" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Emperor Cobra"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Emperor Cobra"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +13, Survival: +11"
abilityMods: [6, 4, 4, -4, 2, -2]
speed: 25 feet,  climb 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +11, __Will__ +9"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+15 (reach 10 feet)\n__Damage__  2d8 + 8 piercing plus emperor-cobra-venom"

  - name: "Emperor Cobra Venom"
    desc: " (poison) **Saving Throw** DC 22 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d8 poison damage (1 round)\n\n**Stage 2** 1d8 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 3** 2d6 poison damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "Flare Hood"
    desc: "`pf2:1` (emotion,fear,mental,visual) The emperor cobra flares its hood. Each non-emperor cobra creature within a 20-foot emanation must attempt a DC 22 Will check save. The creature is then temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]]."
 
```

```encounter-table
name: Emperor Cobra
creatures:
  - 1: Emperor Cobra
```



These aggressive serpents infest bogs and lowlands. Despite a length of over 16 feet and weighing over 200 pounds, they can climb trees in seconds. An emperor cobra wards off predators by flaring its hood and hissing at its attacker.
