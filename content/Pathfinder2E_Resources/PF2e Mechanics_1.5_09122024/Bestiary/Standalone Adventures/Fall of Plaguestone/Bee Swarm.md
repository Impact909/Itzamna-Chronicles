---
title: "Bee Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PYz74DHmhS2V1xfo" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Bee Swarm"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Bee Swarm"
level: "Creature 1"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Stealth: +7"
abilityMods: [-1, 4, 1, -5, 1, -4]
speed:  fly 20 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +4, __Ref__ +9, __Will__ +4"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "Beestings"
    desc: " (poison) The creature must attempt a DC 16 Fortitude check save. Those who fail take 1d4 poison damage and are [[Conditions/Clumsy|Clumsy 1]] for 1 minute."

  - name: "Swarming Stings"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 1d4 piercing damage (DC 16 Reflex check save). The first time each round a creature fails the save and takes piercing damage, it also suffers the effect of beestings.\n\nWhenever the bee swarm uses this ability, the swarm takes 1 damage."
 
```

```encounter-table
name: Bee Swarm
creatures:
  - 1: Bee Swarm
```




