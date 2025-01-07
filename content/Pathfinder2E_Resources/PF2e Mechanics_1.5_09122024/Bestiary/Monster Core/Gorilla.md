---
title: "Gorilla"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NezQaUkUDFCuqZW2" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Gorilla"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gorilla"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +11, Stealth: +7"
abilityMods: [4, 2, 3, -4, 1, -2]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +12, __Ref__ +9, __Will__ +6"
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

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (agile, reach 10 feet)\n__Damage__  2d6 + 4 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d8 + 4 piercing"

  - name: "Frightening Display"
    desc: "`pf2:2` (auditory,emotion,fear,mental) The gorilla beats its chest in a terrifying display. Creatures within 30 feet must attempt a DC 20 Will check save.\n\nWhile a creature is [[Conditions/Frightened|Frightened]] by this ability, it is [[Conditions/Off-Guard|Off-Guard]] to the gorilla.\n* * *\n\n**Critical Success** No effect and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 2]]."
 
```

```encounter-table
name: Gorilla
creatures:
  - 1: Gorilla
```



Gorillas can be territorial creatures, particularly if provoked by hunters or the presence of more dangerous monsters. A gorilla uses its fangs and powerful arms to bite and pummel trespassers with wild abandon.

* * *

While many apes exhibit peaceful or reclusive behavior, gorillas can be territorial, and the megaprimatus is especially aggressive and dangerous.
