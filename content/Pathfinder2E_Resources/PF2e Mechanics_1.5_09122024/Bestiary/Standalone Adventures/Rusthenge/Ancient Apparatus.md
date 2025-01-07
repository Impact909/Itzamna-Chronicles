---
title: Ancient Apparatus
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Rusthenge
aliases: "Actor.0WqBrTGVBEsMeihQ" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Ancient Apparatus"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +5, __Ref__ +11, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 8; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 8" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A complex device made of multicolored metal that resembles a combination of grinding gears, spider-like legs, and twitching blades, from which emits a constant soft ticking sound. All of the metal in the device appears to be rusted or corroded."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check to adjust the device's workings so they seize up and no longer function, or DC 21 Religion check to focus prayers to a non-evil deity into the device to disrupt its ability to channel ambient faith"
attacks:
  - name: ""

  - name: "Spin Up"
    desc: "`pf2:r` **Trigger** The ancient apparatus takes damage or an attempt to disable it fails\n* * *\n\n**Effect** The ancient apparatus begins to grind and churn faster. Its soft ticking whirs up to a discordant buzzing sound, and the entire thing begins to glow with an unsettling rust-colored light. All living creatures in area **D3** experience the unsettling taste of rust in their mouths and must succeed on a DC 18 Fortitude check save to avoid becoming [[Conditions/Sickened|Sickened 1]]. The ancient apparatus then rolls initiative."
  - name: "Melee"
    desc: "Rusty Light Beam +11 (divine) "

  - name: "Rust Creep"
    desc: "passive (disease, divine) Those afflicted by rust creep develop uncomfortable rust-colored bruises on their flesh and endure full-body aches like those one might experience after a long workout. As the affliction progresses, their bodies—as well as the clothing and items they wear or carry—increasingly break down until a painful death occurs. If a character successfully resists contracting rust creep, or recovers from a case of rust creep, they are temporarily immune to future rust creep infections for 24 hours.\n\n**Saving Throw** DC 15 Fortitude check\n\n**Stage 1** –1 status penalty to Athletics checks (1 day)\n\n**Stage 2** as stage 1 (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 4** enfeebled 1 and [[Conditions/Stupefied|Stupefied 1]], plus any armor, clothing and items you carry and that are of a level equal to or less than the disease become broken as the decay spreads to them (1 day; broken items remain broken)\n\n**Stage 5** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 6** unconscious (1 day)\n\n**Stage 7** death"

  - name: "Routine"
    desc: "(3 actions) The ancient apparatus emits beams of rust-colored light, spending an action to make ranged Strikes against three targets in area **D3**. The apparatus can target creatures as if it possessed darkvision, but has no ability to discern between friend or foe. It can't target a creature more than once, and if there are more than three targets, it selects its targets from those it can see in the room randomly. The ancient apparatus has only 1 action as long as its Hit Points are below its BT."
  - name: "Reset"
    desc: "The ancient apparatus reverts to its non-active mode and resets automatically at the end of any round in which there are no obvious targets to attack."
```

```encounter-table
name: Ancient Apparatus
creatures:
  - 1: Ancient Apparatus
```

