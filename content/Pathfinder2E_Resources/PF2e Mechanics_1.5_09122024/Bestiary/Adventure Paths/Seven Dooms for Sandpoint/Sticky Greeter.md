---
title: Sticky Greeter
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.vooKsFHVmfMsiy7K" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Sticky Greeter"
level: "Hazard 5"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +15, __Ref__ +9, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40; __Hardness__ 5; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: " +13"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A taxidermy giant spider's abdomen opens up to spray the area in front of it with sticky webbing."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Thievery check to disable the pressure plate that triggers the sticky greeter."
attacks:
  - name: ""

  - name: "Web"
    desc: "passive **Web Hardness** 5\n\n**Web HP** 20\n\n**Immunities** bludgeoning damage, critical hits, object immunities, piercing damage, precision damage"

  - name: "Spray Webbing"
    desc: "`pf2:r` **Trigger** A creature steps on the pressure plate adjacent to the sticky greeter\n* * *\n\n**Effect** The sticky greeter lurches as its abdomen snaps forward, opens, and sprays the triggering creature with thick sheets of alchemical webbing. At the same time, the sticky greeter emits a high-pitched whistling sound. The creature must make a DC 26 Reflex check save or become [[Conditions/Immobilized|Immobilized]] and held in place, or [[Conditions/Restrained|Restrained]] on a critical failure until it [[Actions/Escape|Escapes]] (DC 22) or the webbing binding it is destroyed."


  - name: "Reset"
    desc: "The sticky greeters must be reset manually."
```

```encounter-table
name: Sticky Greeter
creatures:
  - 1: Sticky Greeter
```

