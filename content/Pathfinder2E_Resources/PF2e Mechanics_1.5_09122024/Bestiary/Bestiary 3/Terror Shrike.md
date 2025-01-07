---
title: "Terror Shrike"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.j5JkCaXeMW4RyFhL" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Terror Shrike"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Terror Shrike"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +13"
abilityMods: [5, 4, 3, -4, 1, 0]
speed: 60 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +12, __Will__ +7"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+13 (reach 10 feet)\n__Damage__  2d8 + 5 piercing plus tearing-clutch"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+13 (agile)\n__Damage__  2d6 + 5 piercing plus knockdown"

  - name: "Sprint"
    desc: "`pf2:2`  **Frequency** once per minute\n* * *\n\n**Effect** The terror shrike Strides three times in a straight line."

  - name: "Stunning Screech"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The terror shrike unleashes a haunting screech that causes prey to freeze in fear. Each creature in a 30-foot emanation other than terror birds must attempt a DC 19 Will check save. Regardless of the result, creatures are then temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Off-Guard|Off-Guard]] until the start of its turn.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 2]]."

  - name: "Sudden Charge"
    desc: "`pf2:2`  The terror shrike Strides twice. If it ends its movement within melee reach of one creature, it can make a melee Strike against that creature."

  - name: "Tearing Clutch"
    desc: "  The terror bird's powerful beak can tear through flesh. On a successful beak Strike, the target takes 1 bleed damage. This bleed damage increases to 1d8 bleed on a critical hit."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Terror Shrike
creatures:
  - 1: Terror Shrike
```



The terror shrike, also known as the scythe beak, is a more powerful species of terror bird. Large terror bird flocks typically have one or two terror shrikes as leaders.

* * *

Terror birds aren't one species but rather a family of deadly, flightless avian predators. All terror birds are capable of bursts of great speed and have powerful beaks that can tear apart the flesh of their prey. Most stalk large, open prairies and steppes, competing directly with other sizable predators such as large cats and wolves.
