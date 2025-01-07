---
title: "Squirrelwind"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.D2YyD2ufbRig9NDa" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/animal
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Squirrelwind"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog: April Fool&#x27;s Bestiary"
name: "Squirrelwind"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[animal]]
trait_03: [[elemental]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Stealth: +16"
abilityMods: [6, 7, 3, 0, 3, 0]
speed:  fly 75 feet
sourcebook: "_Pathfinder Blog: April Fool&#x27;s Bestiary_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +15, __Ref__ +23, __Will__ +17"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130; __Immunities__  paralyzed,  poison,  precision,  sickened,  sleep,  swarm mind; __Resistances__ physical 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "Chittering"
    desc: " (auditory,aura) 60 feet. The chitters of wind-buffeted squirrels disrupts the senses, making air and ground within the emanation difficult terrain for all creatures that hear the sound."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+22 (finesse, reach 20 feet)\n__Damage__  2d12 + 10 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Squirrel"
    desc: "+22 (deadly d10, thrown 30 ft., versatile s)\n__Damage__  2d4 + 10 bludgeoning"

  - name: "Squirrel Surge"
    desc: "`pf2:1` (flourish) Each enemy within the squirrelwind's chittering aura takes 1d8 slashing damage."

  - name: "Swiftness"
    desc: "  The squirrelwind's movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Squirrelwind
creatures:
  - 1: Squirrelwind
```




