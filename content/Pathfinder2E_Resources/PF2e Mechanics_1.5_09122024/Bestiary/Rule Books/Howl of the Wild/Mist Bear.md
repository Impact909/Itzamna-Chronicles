---
title: "Mist Bear"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rctDdBC9dSXWMggD" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/ethereal
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Mist Bear"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Mist Bear"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[ethereal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17, Survival: +15"
abilityMods: [6, 2, 5, -3, 4, 2]
speed: 35 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +13, __Will__ +15"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140"
abilities_top:
  - name: ""

  - name: "Mist Form"
    desc: " (concentrate,exploration,occult,polymorph) Over the course of a minute, a mist bear can transmute its form into a cloud of ethereal vapor. In this state it has resistance 10 to physical damage, is immune to precision damage, and can't use any actions with the attack or manipulate trait. It has a fly Speed of 10 feet and can slip through tiny cracks. The mist bear can return to solid form as a single action."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 ()\n__Damage__  2d10 + 8 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  2d8 + 8 slashing plus grab"

  - name: "Clouded Charge"
    desc: "`pf2:2` (concentrate,occult,visual) The mist bear Strides twice. During this movement, wisps of ethereal smoke trail from its body, making it [[Conditions/Concealed|Concealed]]. The mist bear then Strikes. The target is [[Conditions/Off-Guard|Off-Guard]] to this attack if the bear moved at least 20 feet."

  - name: "Misty Mauling"
    desc: "`pf2:1` (concentrate,occult,polymorph) **Requirements** The mist bear has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The mist bear digs its claws into the grabbed creature as it dissipates into mist. The grabbed creature takes 3d8 slashing damage (DC 25 Fortitude check save). The mist bear gains the benefits of its Mist Form, Flies up to 10 feet, and then returns to its solid form."
 
```

```encounter-table
name: Mist Bear
creatures:
  - 1: Mist Bear
```



Like the mundane bears they resemble, a mist bear is motivated by simple pursuits, such as food. Unlike other ursines, the mist bear can dissipate into a cloud of ethereal vapor, greatly complicating the efforts of neighboring humanoids to keep their provisions safe from the creature's depredations.

Fortunately, the mist bear follows a predictable pattern of behavior, usually foraging within the Universe for only a few months every year to gorge itself. Once sated, it then enters a state similar to hibernation where it drifts through the Ethereal Plane as a cloud of intangible vapor.
