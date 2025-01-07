---
title: "Tardigrade Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NPVs1U5ya7wimarS" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Tardigrade Swarm"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Tardigrade Swarm"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +19, Survival: +21"
abilityMods: [2, 4, 6, -5, 3, 1]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +26, __Ref__ +21, __Will__ +19"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  precision,  swarm mind; __Resistances__ all damage 5 (except area damage)"
abilities_top:
  - name: ""

  - name: "Eyespots"
    desc: "  A tardigrade swarm can't see anything beyond 30 feet."

abilities_mid:
  - name: ""
  - name: "Tun Marbles"
    desc: "  As the tardigrade swarm is damaged, the bodies of those that enter a tun state make the ground treacherous. When the tardigrade swarm drops below 70 Hit Points, the space they occupy is considered difficult terrain."

attacks:
  - name: ""

  - name: "Stylets"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 4d8 piercing damage (DC 32 Reflex check save). Creatures that fail their save become [[Conditions/Drained|Drained 1]] or increase their drained condition by one, to a maximum of [[Conditions/Drained|Drained 4]]."
 
```

```encounter-table
name: Tardigrade Swarm
creatures:
  - 1: Tardigrade Swarm
```




