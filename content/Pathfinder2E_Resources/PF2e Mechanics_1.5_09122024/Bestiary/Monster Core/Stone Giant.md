---
title: "Stone Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NG99u4LAPuFRCyuV" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Stone Giant"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Stone Giant"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[giant]]
trait_03: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Jotun, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +20, Intimidation: +14, Nature: +18, Stealth: +14"
abilityMods: [6, 2, 4, 0, 4, 0]
speed: 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +14, __Will__ +14"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|+1 Striking Greatclub]]"
abilities_mid:
  - name: ""
  - name: "Swat Projectile"
    desc: "`pf2:r`  **Requirements** The stone giant must have a free hand but can Release anything as part of this reaction\n\n**Trigger** The giant is targeted by a physical ranged attack\n* * *\n\n**Effect** The stone giant gains a +4 circumstance bonus to AC against the triggering attack. If the attack misses and the projectile was made of stone, the giant can throw it back at the attacker as a rock ranged Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+21 (backswing, magical, reach 10 feet, shove)\n__Damage__  2d10 + 12 bludgeoning"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, reach 10 feet)\n__Damage__  2d6 + 14 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+18 (brutal, range increment 120 feet)\n__Damage__  2d6 + 12 bludgeoning"

  - name: "Big Swing"
    desc: "`pf2:2`  The stone giant makes a greatclub Strike. The target is Pushed up to 10 feet on a hit or up to 20 feet on a critical hit.\n\nIf the target collides with a solid object, it takes bludgeoning damage as though it had fallen the distance it moved."

  - name: "Create Boulder"
    desc: "`pf2:1` (earth,primal) The stone giant molds a boulder from primal earth and throws it as a rock Strike. A creature hit by the Strike must succeed at a DC 26 Reflex check save or be knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Stone Giant
creatures:
  - 1: Stone Giant
```



Stone giants are stoic, reclusive herders and artists with a rich history and collection of traditions. They dwell in caves in tall mountains and craggy ranges, where their grayish skin allows them to blend in with their surroundings and go unnoticed, despite being around 12 feet tall. Benign travelers who come across a clan of stone giants need not worry, however, for stone giants do not actively invite confrontation or strife. They are, by and large, peaceful people who seek wisdom through exploration of nature and long meditations on the elements of the natural world. Their elders are among the wisest of giants, using their charisma and druidic magic to lead their clans to prosperity and harmony with nature.

A stone giant clan will usually raise a number of animals as pets, favoring cave bears, elephants, or dinosaurs depending on the environment. Many clans also accept allies, considering arboreals, elementals, and even gargoyles as kin through their shared connection with the earth.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
