---
title: "Pinacosaurus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tvBiSv7Z3Dt0BEIm" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Pinacosaurus"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Pinacosaurus"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13"
abilityMods: [5, 0, 4, -4, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +8, __Will__ +8"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+13 (backswing, reach 10 feet)\n__Damage__  2d6 + 5 bludgeoning plus punishing-tail"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+13 ()\n__Damage__  1d8 + 5 bludgeoning"

  - name: "Punishing Tail"
    desc: "  A creature hit by the pinacosaurus's tail must attempt a DC 21 Fortitude check save. On a failure, it's [[Conditions/Slowed|Slowed 1]] until the end of its next turn; on a critical failure, it's [[Conditions/Stunned|Stunned]] until the end of its next turn."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Small or smaller, foot, DC 21 Reflex check save\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Pinacosaurus
creatures:
  - 1: Pinacosaurus
```




