---
title: "Giant Flea"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EHHc3kNfvJHhS0CS" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Giant Flea"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Giant Flea"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +9"
abilityMods: [2, 3, 3, -5, 1, -4]
speed: 30 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +12, __Will__ +4"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  disease"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Proboscis"
    desc: "+10 ()\n__Damage__  1d8 + 4 piercing plus suck-blood,flea-fever"

  - name: "Flea Fever"
    desc: " (disease) Drain from flea fever can't be reduced or recovered from naturally until the disease is cured.\n\n**Saving Throw** DC 18 Fortitude check\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1d4 hours)\n\n**Stage 2** drained 1 and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] and sickened 1 (1 day)\n\n**Stage 4** [[Conditions/Drained|Drained 3]] and sickened 1 (1 day)\n\n**Stage 5** dead"

  - name: "Suck Blood"
    desc: "`pf2:1`  **Requirements** The giant flea's last action was a successful proboscis Strike\n* * *\n\n**Effect** The giant flea drinks the creature's blood. The victim becomes [[Conditions/Drained|Drained 1]] and the flea regains 5 healing HP."
 
```

```encounter-table
name: Giant Flea
creatures:
  - 1: Giant Flea
```



Giant fleas are commonly found in areas containing hardy megafauna, such as dinosaurs or mammoths.

* * *

Fleas are little more than a nuisance in most circumstances, but can be lethal when they grow to monstrous proportions or gather in enormous swarms.
