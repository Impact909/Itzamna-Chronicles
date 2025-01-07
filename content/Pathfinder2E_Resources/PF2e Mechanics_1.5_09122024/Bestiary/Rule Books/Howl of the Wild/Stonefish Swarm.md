---
title: "Stonefish Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wgnGdhHZvlO9DISS" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Stonefish Swarm"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Stonefish Swarm"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
trait_03: [[swarm]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +6, Stealth: +11"
abilityMods: [2, 3, 2, -5, 1, -1]
speed:  swim 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +11, __Ref__ +8, __Will__ +5"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 3, splash damage 3; __Resistances__ bludgeoning 3, slashing 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Actor.3A8vgAWozHIc7gbY.Item.1f2PgrJfd3BP5KWT|Defensive Spines]]"
    desc: "  When a creature enters the stonefish swarm's space, that creature takes 1d4 piercing damage and is exposed to stonefish swarm venom."

  - name: "Reef Camouflage"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the stonefish swarm appears to be a colorful coral reef. It has an automatic result of 26 on Deception checks and DCs to pass as a reef."

attacks:
  - name: ""

  - name: "Inject Poison"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 2d4 piercing damage (DC 18 Reflex check save). Creatures that fail the save are exposed to stonefish swarm venom."

  - name: "Stonefish Swarm Venom"
    desc: " (poison) **Saving Throw** DC 18 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 1d6 poison and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 2d6 poison damage and clumsy 2 (1 round)"
 
```

```encounter-table
name: Stonefish Swarm
creatures:
  - 1: Stonefish Swarm
```



Stonefish occasionally band together where food is abundant, filling all nooks and crannies of a coral reef. In large numbers, stonefish can take on prey much larger than themselves.
