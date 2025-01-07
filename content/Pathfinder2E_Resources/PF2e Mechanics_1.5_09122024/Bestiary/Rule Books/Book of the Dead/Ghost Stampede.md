---
title: Ghost Stampede
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Book of the Dead
aliases: "Actor.yYQJU3p2jQkm9lM3" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ghost Stampede"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 30
sourcebook: "_Pathfinder Book of the Dead_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +23, __Ref__ +29, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20, per aurochs skull; __Hardness__ 25; __Immunities__  object immunities,  death effects,  disease,  paralyzed,  poison; __Weaknesses__ vitality 5"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four massive skulls of aurochs, enormous wild cattle, rise into the air, each trailing its ghostly body behind it."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 36 Nature check (master) to calm one of the four aurochs or DC 40 Religion check (trained) to exorcise them"
attacks:
  - name: ""

  - name: "Defend Territory"
    desc: "`pf2:r` (emotion, fear, mental, occult) **Trigger** A creature approaches within 10 feet of an aurochs skull\n* * *\n\n**Effect** The skulls rise into the air, form ghostly bodies, and bellow in rage. Each creature within 60 feet of an aurochs skull must attempt a DC 36 Will check saving throw. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes 1d12+6 mental damage and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature takes 2d12+12 mental damage and is [[Conditions/Frightened|Frightened 4]]."
  - name: "Melee"
    desc: "Horn +30 () No multiple attack penalty"

  - name: "Routine"
    desc: "(4 actions) For each aurochs skull disabled or destroyed, the haunt has 1 fewer action. On each action, a different aurochs moves up to 60 feet and attempts a horn Strike against a different living creature. A creature critically hit by a horn Strike also takes 2d6 bleed and is knocked [[Conditions/Prone|Prone]]."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all living creatures leave the area or after all four aurochs skulls are destroyed. After 1 hour, if at least one aurochs skull remains, the haunt reactivates."
```

```encounter-table
name: Ghost Stampede
creatures:
  - 1: Ghost Stampede
```

