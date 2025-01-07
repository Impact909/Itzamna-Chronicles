---
title: "Apothecary Bee"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0BwSDlVw85EtFyJt" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Apothecary Bee"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Apothecary Bee"
level: "Creature 7"

alignment: ""
size: "tiny"
trait_01: [[animal]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Stealth: +17, Thievery: +15"
abilityMods: [1, 6, 3, -4, 2, 2]
speed: 10 feet,  climb 10 feet,  fly 50 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +14, __Ref__ +19, __Will__ +13"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Healing Potion (Moderate)|Healing Potion (Moderate)]]"
  - name: "Drain Potion"
    desc: "`pf2:2` (manipulate) **Requirements** The apothecary bee has no stored potions\n* * *\n\n**Effect** The apothecary bee slurps up a potion within its reach, storing it internally. A creature can attempt a DC 25 Reflex check save to protect a potion in its possession."

  - name: "Ingest Potion"
    desc: "`pf2:1`  The apothecary bee consumes the potion it has stored in its body. If the potion has the healing trait, the apothecary bee heals for the maximum amount."

  - name: "Inject Potion"
    desc: "`pf2:1` (manipulate) The apothecary bee injects its stored potion into a willing creature within its reach. This deals 1 piercing damage and grants the recipient the normal effects of drinking the potion."

  - name: "Internal Cauldron"
    desc: "  With an appropriate diet, an apothecary bee will create a potion of 6th level or lower every two weeks. Most often, this is a [[Equipment/Healing Potion (Moderate)|Healing Potion (Moderate)]]. Each apothecary bee can store only one completed potion at a time. Unused potions can generally be harvested from an apothecary bee with a successful DC 23 Nature check or DC 23 Survival check check."

  - name: "Potionsight"
    desc: "  Apothecary bees' complex eyes let them see the auras of magical potions and instinctively identify potions of their level or lower. These auras are visible through mundane containers, though their eyes have no special ability to perceive or identify non-magical solutions, such as alchemical elixirs."

abilities_mid:
  - name: ""
  - name: "Smoke Susceptibility"
    desc: "  An apothecary bee is [[Conditions/Slowed|Slowed 1]] if it starts its turn in heavy smoke."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+19 (magical, poison)\n__Damage__  1d4 + 4 piercing 3d6 poison"
 
```

```encounter-table
name: Apothecary Bee
creatures:
  - 1: Apothecary Bee
```



These giant bees feed on the nectar of medicinal herbs and magical flowers, naturally processing the liquid into syrupy-sweet potions. Depending on the precise diet of the apothecary bees, they can produce a wide variety of potions, storing any excess in the waxy cells lining their nest. Apothecary bee workers are about a foot long, with yellow and black stripes. While carrying a potion, the bee's abdomen visibly swells and often changes color to match the potion within.

The value of the apothecary bees' potions has led to numerous attempts at domestication, a dangerous, expensive dream with both high risks and high rewards. Once a magical garden has been established, apothecary beehives tend to become self-sustaining. Beekeepers can potentially guide their cultivation, but they're no longer necessary for the hive's survival. Some ancient, long-abandoned gardens still grow along the Sphinx River in Osirion, where many apothecary bees prowl for flowers that meet their standards. Upon their most recent dig to the surface, surki communities quickly began the process of "trading" with the bees, establishing habitats and using their natural magic sense to better tend the massive fields a large hive needs. Miflits, on the other hand, often end up absorbed into the bees' social structure.

The potions a hive produces vary from season to season, depending on what flowers are available. Beekeepers have made strides in creating gardens that yield specific potions and have even developed harvesting techniques that increase potion effectiveness. These techniques are valuable, closely guarded secrets, but even defective potions with cursed results have found use among the followers of Calistria and Norgorber.
