---
title: "Wasp Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nx6rWrZDvauGRkfM" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Wasp Swarm"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Wasp Swarm"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +12"
abilityMods: [-4, 4, 2, -5, 2, -1]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +12, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 7, piercing 7, slashing 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Swarming Stings"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 2d8 piercing damage (DC 21 Reflex check save). A creature that fails its save is also exposed to wasp venom."

  - name: "Wasp Venom"
    desc: " (poison) **Saving Throw** DC 21 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison (1 round)\n\n**Stage 2** 2d6 poison and [[Conditions/Clumsy|Clumsy 2]] (2 rounds)"
 
```

```encounter-table
name: Wasp Swarm
creatures:
  - 1: Wasp Swarm
```



Wasp nests are made of chewed wood fibers foraged from the surrounding flora, which the wasps make into a material similar to paper. A single wasp nest can house thousands of individuals that emerge as a massive swarm. Most swarms attack only to protect their nest or if otherwise agitated, though druids and other primal enchanters can bend these venomous vermin to their will—to deadly effect.

* * *

While the common wasp poses little threat to a hardy adventurer aside from an uncomfortable sting, a large and aggressive swarm of these territorial insects—to say nothing of their oversized kin—can lay low an entire party of heroes. The wasps represented here are of the common variety, also known as yellow jackets, but many other sorts of dangerous wasps exist, such as a Garundi variant that swarms in such great numbers that it can decimate entire villages.
