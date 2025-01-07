---
title: "Spider Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WA8nxFChyLc4wvN8" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Spider Swarm"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Spider Swarm"
level: "Creature 0"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +2, Stealth: +5"
abilityMods: [-2, 3, 0, -5, 0, -4]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +4, __Ref__ +7, __Will__ +2"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "Web Sense"
    desc: "  The spider swarm has imprecise tremorsense to detect the vibrations of creatures touching its web.\n* * *\n\nTremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Spider Swarm Venom"
    desc: " (poison) **Saving Throw** DC 14 Fortitude check\n* * *\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1 poison and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d4 poison and enfeebled 1 (1 round)"

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the spider swarm's space takes 1d4 piercing damage with a DC 14 Reflex check save.\n\nA creature that fails its save is exposed to spider swarm venom."
 
```

```encounter-table
name: Spider Swarm
creatures:
  - 1: Spider Swarm
```



An abundance of food, the sudden hatching of a clutch of eggs, or magical influence can cause smaller spiders to gather in terrifying, deadly masses.

* * *

Few everyday vermin inspire as much dread as the infamous spider.
