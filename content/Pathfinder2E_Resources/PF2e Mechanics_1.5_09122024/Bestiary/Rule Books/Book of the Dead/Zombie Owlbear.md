---
title: "Zombie Owlbear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bHiG4JknrZvqlIIi" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Zombie Owlbear"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Zombie Owlbear"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +12"
abilityMods: [4, 0, 3, -5, 1, -3]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +8, __Ref__ +5, __Will__ +6"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Slow"
    desc: "  A zombie owlbear is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Talon"
    desc: "+12 ()\n__Damage__  1d10 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+12 ()\n__Damage__  1d12 + 7 piercing"

  - name: "Ground Slam"
    desc: "`pf2:2` (attack) **Requirements** The zombie owlbear has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] with its talons\n* * *\n\n**Effect** The zombie owlbear repeatedly slams the creature into the ground. This deals 1d10+7 bludgeoning damage (DC 20 Fortitude check). On a critical failure, the creature is [[Conditions/Stunned|Stunned 1]], and on a critical success the creature is no longer grabbed or restrained."

  - name: "Horrifying Screech"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The zombie owlbear unleashes a broken, snarling screech that unnerves those who hear it. Each creature in a 60-foot emanation must attempt a DC 19 Will check save. Regardless of the result, creatures are temporarily immune for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Fleeing|Fleeing]] for 1 round and [[Conditions/Frightened|Frightened 3]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zombie Owlbear
creatures:
  - 1: Zombie Owlbear
```



Zombie owlbears combine an owlbear's ferocity with mindless undead hatred. Once it draws near, it often stands up, unleashing a guttural, wet roar, before charging into combat without thought of self-preservation.

* * *

Simple to create and varied in purpose, these shambling undead are often used for their strength and endless stamina to conduct boring, repetitive tasks.
