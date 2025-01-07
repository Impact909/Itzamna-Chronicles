---
title: Needling Stairs
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #159: All or Nothing
aliases: "Actor.sMSGOTYWS3LbSJ6T" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Needling Stairs"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 20
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +19, "
hp: 25
health:
  - name: ""
  - name: "HP"
    desc: "25, to break the spring under the step and make that step safe to stand on; __Hardness__ 8; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "This staircase has springs in each step, which send poisoned needles shooting up through tiny holes in the wood when stepped on. Each step, 6 in total, takes up one 5-foot square."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) on each stair to disable its spring, or deactivate the switch in area **C8** to deactivate the whole trap. Cutting the wire on the topmost stair (>DC 35 Thievery check to Disable the Device) that connects the staircase to the control switch prevents the control switch from turning the trap on or off."
attacks:
  - name: ""

  - name: "First Step"
    desc: "`pf2:r` **Trigger** A creature ends its movement on one of the stairs\n* * *\n\n**Effect** The trap makes a poisoned needle Strike against the triggering creature, then rolls initiative."
  - name: "Melee"
    desc: "Poisoned Needle +24 () No MAP applies to strikes made by poisoned needle attacks"

  - name: "Bloody Feet"
    desc: "`pf2:0` **Trigger** A creature moves onto an active step\n* * *\n\n**Effect** The trap makes a poisoned needle Strike against the triggering creature."

  - name: "No MAP"
    desc: "passive The Poisoned Needle Strikes do not apply a MAP."

  - name: "Routine"
    desc: "(1 action) The trap makes a separate poisoned needle Strike against each creature currently on an active step as 1 action. Because it is constantly jabbing needles up through any weight-bearing steps, the trap can also use its Bloody Feet free action to jab at a creature on one of the steps during that creature's turn."
  - name: "Reset"
    desc: "If deactivated via the switch, the trap can be reactivated with the switch in area **C8**."
```

```encounter-table
name: Needling Stairs
creatures:
  - 1: Needling Stairs
```

