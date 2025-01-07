---
title: Myristica's Despair
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #201: Pactbreaker
aliases: "Actor.spshz2oCqCeR5DQ2" 
level: 5
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Myristica's Despair"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 13
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +11, __Ref__ +15, __Will__ +15"
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 8"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(expert) to recognize that the scene before them is an illusion."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The illusion shatters, revealing the grove to be a lifeless scar and the seemingly peaceful loggers to be crawling aimlessly about the clearing, consumed by rage and lashing out at anything that comes near."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Nature check (trained) to tame the primal energy, DC 23 Diplomacy check (trained) to console the dryad, DC 24 Occultism check (trained) to identify and heal the emotional wounds; three successes are required to disable the haunt."
attacks:
  - name: ""

  - name: "Awaken"
    desc: "`pf2:r` (emotion, fear, mental, primal) **Trigger** At least two creatures enter the grove\n* * *\n\n**Effect** The illusion fades, and a sorrowful chill emanates from the giant tree. The haunt rolls initiative."

  - name: "Routine"
    desc: "(1 action; emotion, mental, primal) Myristica bemoans her grove's fate, overwhelming foes with sorrow. Each creature in the grove must attempt a DC 23 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Dazzled|Dazzled]] for 1 round and takes 2d6 mental damage.\n\n**Critical Failure** The creature takes 2d6 mental damage, plus 2d6 persistent mental damage. While taking this persistent damage, they are dazzled."
  - name: "Reset"
    desc: "Unless Silene is destroyed, this haunt can recharge itself after 1 hour."
```

```encounter-table
name: Myristica's Despair
creatures:
  - 1: Myristica's Despair
```

