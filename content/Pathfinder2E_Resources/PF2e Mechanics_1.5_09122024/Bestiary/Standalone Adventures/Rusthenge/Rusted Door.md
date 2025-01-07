---
title: Rusted Door
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: Rusthenge
aliases: "Actor.FQmjyvu7qJyPxbxA" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Rusted Door"
level: "Hazard 2"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +11, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 8; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Shards of rust extend from the door and crumble away to cling to the flesh and clothes of anyone who attempts to open or damage the door."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check to deface the hidden runes that allow the trap to activate, or DC 21 Religion check to offer prayers to a non-evil deity to override the ancient influence of Xar-Azmak"
attacks:
  - name: ""

  - name: "Inflict Rust Creep"
    desc: "`pf2:r` **Trigger** A non-worshipper of Xar-Azmak attempts to open the door or causes damage to it with a melee Strike\n* * *\n\n**Effect** The triggering creature is exposed to rust creep as tendrils of rust-red energy seem to slither out of the rusty patches on the door to rasp strangely gently against exposed skin."

  - name: "Rust Creep"
    desc: "passive (disease, divine) Those afflicted by rust creep develop uncomfortable rust-colored bruises on their flesh and endure full-body aches like those one might experience after a long workout. As the affliction progresses, their bodies—as well as the clothing and items they wear or carry—increasingly break down until a painful death occurs. If a character successfully resists contracting rust creep, or recovers from a case of rust creep, they are temporarily immune to future rust creep infections for 24 hours.\n\n**Saving Throw** DC 15 Fortitude check\n\n**Stage 1** –1 status penalty to Athletics checks (1 day)\n\n**Stage 2** as stage 1 (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 4** enfeebled 1 and [[Conditions/Stupefied|Stupefied 1]], plus any armor, clothing and items you carry and that are of a level equal to or less than the disease become broken as the decay spreads to them (1 day; broken items remain broken)\n\n**Stage 5** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 6** unconscious (1 day)\n\n**Stage 7** death"


  - name: "Reset"
    desc: "The rusted door resets automatically after 1 round."
```

```encounter-table
name: Rusted Door
creatures:
  - 1: Rusted Door
```

