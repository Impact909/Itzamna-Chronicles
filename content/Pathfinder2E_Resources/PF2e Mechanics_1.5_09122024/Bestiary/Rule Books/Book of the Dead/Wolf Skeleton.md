---
title: "Wolf Skeleton"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SpqzZLT2ETSgEAFT" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Wolf Skeleton"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Wolf Skeleton"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[skeleton]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +4, Stealth: +6"
abilityMods: [2, 4, 1, -5, 2, 0]
speed: 35 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +3, __Ref__ +8, __Will__ +6"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+8 ()\n__Damage__  1d4 + 2 piercing plus knockdown"

  - name: "Surge of Speed"
    desc: "`pf2:2`  The wolf skeleton Strides three times, but it's [[Conditions/Off-Guard|Off-Guard]] until the start of its next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Wolf Skeleton
creatures:
  - 1: Wolf Skeleton
```



Without the burden of flesh, skeletal wolves charge across the battlefield with terrifying speed.

* * *

Among the ranks of the dead, none are so numerous, nor so varied, as the skeleton. While most are almost entirely made from bone, some maintain a few scraps of flesh to aid them in movement, such as wing membranes.
