---
title: "Skeletal Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TvrD9O7tXP4RwyHg" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Skeletal Giant"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Skeletal Giant"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[skeleton]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +9"
abilityMods: [5, 1, 3, -5, 0, 2]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +8, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed,  mental; __Resistances__ cold 5, electricity 5, fire 5, piercing 5, slashing 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|Glaive]], [[Equipment/Half Plate|Half Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+12 (deadly d8, forceful, reach 15 feet)\n__Damage__  1d8 + 7 slashing"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+12 (agile)\n__Damage__  1d10 + 5 piercing"

  - name: "Broad Swipe"
    desc: "`pf2:2`  The giant makes two Strikes with its glaive against two adjacent foes, both of whom are within its reach. Both attacks count toward the giant's multiple attack penalty, but the penalty doesn't increase until after both attacks."

  - name: "Terrifying Charge"
    desc: "`pf2:2`  The giant Strides and makes a horns Strike with a +4 circumstance bonus to damage.\n\nIf the strike hits, the giant attempts to [[Actions/Demoralize|Demoralize]] the target."
 
```

```encounter-table
name: Skeletal Giant
creatures:
  - 1: Skeletal Giant
```



The reanimated bones of giants make excellent necromantic thralls.

* * *

Animated skeletons are among the most common types of undead.
