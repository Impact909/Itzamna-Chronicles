---
title: "Megaprimatus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uCCyzMiWxuMMWZRq" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Megaprimatus"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Megaprimatus"
level: "Creature 8"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +19"
abilityMods: [7, 2, 5, -4, 1, 2]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +19, __Ref__ +16, __Will__ +13"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+21 (agile, reach 20 feet)\n__Damage__  2d8 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (reach 10 feet)\n__Damage__  2d10 + 10 piercing"

  - name: "Mangling Rend"
    desc: "`pf2:2`  A megaprimatus makes two fist Strikes against the same target. If both hit, the attack deals an additional 2d6 bludgeoning damage, the target is [[Conditions/Off-Guard|Off-Guard]], and the target takes a -20-foot status penalty to all Speeds until the end of its next turn.\n\n[[Bestiary Effects/Effect_ Mangling Rend|Effect: Mangling Rend]]"

  - name: "Terrifying Display"
    desc: "`pf2:2` (auditory,emotion,fear,mental) The megaprimatus beats its chest in a terrifying display. Creatures within 50 feet must attempt a DC 27 Will check save.\n\nWhile a creature is [[Conditions/Frightened|Frightened]] by this ability, it is [[Conditions/Off-Guard|Off-Guard]] to the megaprimatus and to gorillas.\n* * *\n\n**Critical Success** No effect and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Fleeing|Fleeing]] until the end of its next turn."
 
```

```encounter-table
name: Megaprimatus
creatures:
  - 1: Megaprimatus
```



The megaprimatus is among the mightiest of apes, quick to confront any perceived intrusions into its domain. With a height of 40 feet, it towers over even most giants, and is used to being the top-tier predator in the region.

* * *

While many apes exhibit peaceful or reclusive behavior, gorillas can be territorial, and the megaprimatus is especially aggressive and dangerous.
