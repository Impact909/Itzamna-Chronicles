---
title: "Griffon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lj1aNGKSMCgbmJXx" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Griffon"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Griffon"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +12, Intimidation: +10, Stealth: +11, Survival: +9"
abilityMods: [4, 3, 3, -4, 1, 2]
speed: 25 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +13, __Will__ +7"
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
    desc: "+14 (deadly d10)\n__Damage__  2d8 + 4 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+14 (agile)\n__Damage__  2d6 + 4 piercing"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+14 (reach 10 feet)\n__Damage__  2d6 + 4 bludgeoning"

  - name: "Flying Strafe"
    desc: "`pf2:2`  The griffon Flies up to its fly Speed and makes two talon Strikes at any point during that movement. Each Strike must target a different creature. The attacks take the normal multiple attack penalty."

  - name: "Pounce"
    desc: "`pf2:1`  The griffon Strides and makes a talon Strike at the end of that movement. If the griffon began this action [[Conditions/Hidden|Hidden]], it remains hidden until after the attack."

  - name: "Regal Shriek"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The griffon unleashes a shriek that transitions into a terrifying roar. Each creature in a 60-foot emanation must attempt a DC 20 Will check save. Regardless of the result, creatures are temporarily immune to all griffons' Regal Shrieks for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]]. Animals are [[Conditions/Slowed|Slowed 1]] for as long as they're frightened.\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]]. Animals are [[Conditions/Paralyzed|Paralyzed]] as long as they're frightened."
 
```

```encounter-table
name: Griffon
creatures:
  - 1: Griffon
```



Griffons are regal beasts revered as symbols of freedom and strength in many cultures. They are physically striking, with the hindquarters of a lion and the head, wings, and forelimbs of a great bird of prey—typically an eagle, but some instead bear the features of a hawk, falcon, or even an osprey or vulture. In rare cases, the griffon's hindquarters may resemble those of a different great cat, such as a leopard or tiger. The variations seem to conform to the griffon's environment—for instance, especially rare griffons of northern Avistan have the hindquarters of a Grungir lynx and the upper body of a snowy owl.

Wild griffons rely on their powerful wings to hold them aloft and their keen eyesight to spy out prey. The speed with which they plunge toward the ground and snatch up victims is astonishing. They often tear apart a kill's flesh with razor-sharp beaks but not before alighting to secluded location where they can enjoy their meal without interruption. Griffons hunting to feed their chicks are more cautious, tearing apart prey rather than risking bringing a living creature back to their nests.

Skilled animal trainers long ago learned how to raise griffons as mounts for military forces or powerful individuals. Such mounts are known for their strength, bravery, and unfailing loyalty. They are among the smartest of animals, and many griffon variants are considered intelligent beasts instead; it's thought that a griffon chooses its rider as much as a rider chooses the griffon. The process of training a griffon to accept and carry a rider in flight is a long and expensive ordeal. Griffon trainers charge rich sums for their services, and a ruler who can boast of owning a stable of griffons is the subject of great respect and envy.
