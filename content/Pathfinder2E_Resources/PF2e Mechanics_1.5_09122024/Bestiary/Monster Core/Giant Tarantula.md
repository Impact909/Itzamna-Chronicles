---
title: "Giant Tarantula"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.o045qyN3wGq3Aqsj" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Giant Tarantula"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Tarantula"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +16, Stealth: +11"
abilityMods: [6, 1, 5, -5, 2, -4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +13, __Will__ +10"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d8 + 8 piercing plus giant-tarantula-venom"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+17 (reach 10 feet)\n__Damage__  1d12 + 8 bludgeoning plus knockdown"

  - name: "Giant Tarantula Venom"
    desc: " (poison) **Saving Throw** DC 23 Fortitude check\n* * *\n\n**Maximum Duration** 8 rounds\n\n**Stage 1** 1d10 poison damage (1 round)\n\n**Stage 2** 1d12 poison damage, [[Conditions/Clumsy|Clumsy 1]], and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and off-guard (1 round)\n\n**Stage 4** 2d6 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "Hair Barrage"
    desc: "`pf2:2`  The tarantula flicks its legs, flinging spiky hairs in a 15-foot cone. This deals 4d6 piercing damage with a DC 25 Reflex check save."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Giant Tarantula
creatures:
  - 1: Giant Tarantula
```



Tarantulas are ambush predators, but will attack prey in the open.

* * *

Few everyday vermin inspire as much dread as the infamous spider.
