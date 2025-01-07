---
title: "Brood Leech Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.c67liZpOHg2VKkYV" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Brood Leech Swarm"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Brood Leech Swarm"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[animal]]
trait_03: [[swarm]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +8, Stealth: +11"
abilityMods: [0, 3, 4, -5, 1, -5]
speed: 5 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +11, __Will__ +9"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, salt 5, splash damage 5; __Resistances__ bludgeoning 2, piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Swarm Mind"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

attacks:
  - name: ""

  - name: "Blood Draining Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 2d6 bleed and is exposed to brood leech swarm venom."

  - name: "Brood Leech Swarm Venom"
    desc: " (poison) **Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Sickened|Sickened 1]], and -5-foot status penalty to Speed (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Sickened|Sickened 1]], and -10-foot status penalty to Speed (1 round)."
 
```

```encounter-table
name: Brood Leech Swarm
creatures:
  - 1: Brood Leech Swarm
```



Most smaller species of leeches do not tend to swarm, but brood leeches are prone to gathering in seething, undulant mats of squirming gluttony. When they gather in sufficient numbers to swarm, they eschew the stealth of a lone leech's feeding methods in favor of swift and merciless feeding. In these situations, their mild venom can affect much larger creatures than their usual prey.
