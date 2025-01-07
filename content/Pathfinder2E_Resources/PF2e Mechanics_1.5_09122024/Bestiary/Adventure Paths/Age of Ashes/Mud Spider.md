---
title: "Mud Spider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kBZxkeU34XiaQzLC" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Mud Spider"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Mud Spider"
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
sourcebook: "_Pathfinder #146: Cult of Cinders_"
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

  - name: "Mudwalking"
    desc: "  The mud spiders ignore difficult terrain from mud."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d8 + 8 piercing plus giant-tarantula-venom"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+17 (reach 10 feet)\n__Damage__  1d12 + 8 bludgeoning plus knockdown"

  - name: "Giant Tarantula Venom"
    desc: " (poison) **Saving Throw** DC 23 Fortitude check\n\n**Maximum Duration** 8 rounds\n\n**Stage 1** 1d6 poison (1 round)\n\n**Stage 2** 1d6 poison, [[Conditions/Off-Guard|Off-Guard]], and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** 1d6 poison, off-guard, and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 4** 1d6 poison and [[Conditions/Paralyzed|Paralyzed]] (1 round)."

  - name: "Hair Barrage"
    desc: "`pf2:2`  The tarantula flicks its legs, flinging spiky hairs in a 15-foot cone. This deals 4d6 piercing damage with a DC 25 Reflex check save."

  - name: "Knockdown"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Mud Spider
creatures:
  - 1: Mud Spider
```


Variant giant tarantula

Tarantulas are ambush predators, but will attack prey in the open.
