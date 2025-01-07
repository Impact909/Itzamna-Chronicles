---
title: Guthallath Rockslide
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #156: The Apocalypse Prophet
aliases: "Actor.VL5Jn4EyF04oDKdE" 
level: 19
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Guthallath Rockslide"
level: "Hazard 19"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 30
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +35, __Ref__ +29, "
hp: 150
health:
  - name: ""
  - name: "HP"
    desc: "150, Hardness 10 in the guthallath&#x27;s erosion aura; __Hardness__ 20; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master) to notice the odd aging of the stones, seemingly far older and more weathered than the surrounding rocks"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The rock walls nearby begin to crumble and collapse."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Crafting check (legendary) to buttress the collapsing rocks in three different locations. Using large and durable materials (or applicable spells) to support the rocks reduces the check to DC 45 Crafting check (master)."
attacks:
  - name: ""

  - name: "Rumbling Rocks"
    desc: "`pf2:r` **Trigger** The guthallath rolls initiative\n* * *\n\n**Effect** The rocks of the area begin to crumble. The hazard rolls for initiative."
  - name: "Melee"
    desc: "Falling Rocks +36 () "

  - name: "Early Collapse"
    desc: "`pf2:0` **Trigger** The hazard takes 30 or more damage\n* * *\n\n**Effect** Move the hazard's initiative to immediately follow the creature that damaged the hazard."

  - name: "Routine"
    desc: "(2 actions) On the hazard's first action, any areas of crumbling rocks from a previous round collapse, making a falling rocks Strike against each creature in the area.\n\nOn its second action, the hazard crumbles rocks in a 20-foot radius around the previous collapse. A character can [[Actions/Seek|Seek]] (DC 40) to determine where the rocks will fall on the following round, but on a critical failure, they incorrectly identify where the rocks will fall."
  - name: "Reset"
    desc: "The guthallath can reset the hazard with a few days of work stacking the fallen rocks."
```

```encounter-table
name: Guthallath Rockslide
creatures:
  - 1: Guthallath Rockslide
```

