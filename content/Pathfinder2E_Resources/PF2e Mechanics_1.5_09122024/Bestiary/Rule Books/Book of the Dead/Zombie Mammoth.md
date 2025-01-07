---
title: "Zombie Mammoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TU6t1O8tRmEaV1IJ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Zombie Mammoth"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Zombie Mammoth"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +24"
abilityMods: [7, 0, 5, -5, 2, -3]
speed: 45 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +22, __Ref__ +15, __Will__ +19"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Severed Trunk"
    desc: "  When the zombie mammoth is hit by a critical hit that deals slashing damage, the mammoth's trunk is severed from its body. Any creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] with the trunk is released, and the mammoth loses its trunk Strike and Greater Constrict.\n\nThe trunk slithers across the battlefield, still animated, and acts in initiative right after the mammoth. It retains Greater Constrict and trunk Strikes but can't use tusk Strikes, foot Strikes, or Shambling Trample. It has all the stats of the mammoth, except its AC is reduced to 23, it has only 50 Hit Points, and its Speed is 10 feet. Damage dealt to the severed trunk has no effect on the zombie mammoth."

  - name: "Slow"
    desc: "  A zombie mammoth is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tusk"
    desc: "+24 (reach 15 feet)\n__Damage__  3d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Trunk"
    desc: "+24 (reach 15 feet)\n__Damage__  2d10 + 7 bludgeoning plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+24 (reach 10 feet)\n__Damage__  2d10 + 13 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d10+7 bludgeoning, DC 30 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "[[Bestiary Ability Glossary/Trample|Shambling Trample]]"
    desc: "`pf2:2`  Large or smaller, foot, DC 30 Reflex check\n\nThe zombie mammoth Strides up to its Speed instead of double.\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Zombie Mammoth
creatures:
  - 1: Zombie Mammoth
```



This monstrous creature can overrun defenses and stomp foes into the ground, making it a terror on any battlefield.

* * *

Simple to create and varied in purpose, these shambling undead are often used for their strength and endless stamina to conduct boring, repetitive tasks.
