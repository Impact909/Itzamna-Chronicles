---
title: Azure Lilies
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.r21eZ9REEf1gWiKR" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Azure Lilies"
level: "Hazard 12"


trait_01: [[environmental]]
modifier: 20
sourcebook: "_Pathfinder Kingmaker_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +27, __Ref__ +25, "
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The azure lilies expel a burst of toxic pollen."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Nature check or DC 33 Survival check (expert) to harvest the plant's pollen without disturbing the blossoms."
attacks:
  - name: ""

  - name: "Pollen Burst"
    desc: "`pf2:r` (emotion, mental, poison) **Trigger** The lily patch is disturbed\n\n**Effect** The pollen erupts in a 30-foot-radius burst. Any living creature in the burst must attempt a DC 30 Will check save, though creatures with the plant trait are immune.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 6d6 mental damage as the pollen causes wracking headaches and jolts of pain.\n\n**Failure** The creature takes 12d6 mental damage and is [[Conditions/Confused|Confused]] for 1 minute. The creature can attempt a new save at the end of each of its turns to end the confusion early.\n\n**Critical Failure** The creature takes 20d6 mental damage and is confused for 1 minute, with no save to end the confusion early."


  - name: "Reset"
    desc: "1 month"
```

```encounter-table
name: Azure Lilies
creatures:
  - 1: Azure Lilies
```

