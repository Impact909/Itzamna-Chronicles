---
title: Trapped Portcullis
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.IAvETOqQ9QdgJo2J" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Trapped Portcullis"
level: "Hazard 11"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 26
sourcebook: "_Pathfinder Kingmaker_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +18, "
hp: 72
health:
  - name: ""
  - name: "HP"
    desc: "72; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 36" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Two portcullises drop down to block progress through this area."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) to disable the trigger that causes the portcullises to drop"
attacks:
  - name: ""

  - name: "Drop From Ceiling"
    desc: "`pf2:r` **Trigger** A character enters a square between the two portcullises\n* * *\n\n**Effect** Both portcullises drop from the ceiling; attempting to lift one requires a DC 30 Athletics check check to [[Actions/Force Open|Force Open]]. When the portcullises drop, creatures in adjacent squares must attempt a DC 30 Reflex check save.\n* * *\n\n**Critical Success** The creature is unharmed and can take a Step as a reaction to move to an adjacent square.\n\n**Success** As critical success, but the creature takes a glancing blow from the falling portcullis for 2d12+15 bludgeoning damage.\n\n**Failure** The creature is struck by the falling portcullis for 4d12+30 bludgeoning damage and is knocked [[Conditions/Prone|Prone]] in their square.\n\n**Critical Failure** The creature is struck by the falling portcullis for 6d12+45 bludgeoning damage, is knocked prone, and is [[Conditions/Immobilized|Immobilized]] by the portcullis as it pins them to the ground until they can [[Actions/Escape|Escape]] or Force Open the portcullis (DC 30, Athletics)."


  - name: "Reset"
    desc: "The trap can be manually reset with a 10-minute Manipulate activity performed in the hallways to the east or west of this area, as long as neither portcullis is broken or destroyed."
```

```encounter-table
name: Trapped Portcullis
creatures:
  - 1: Trapped Portcullis
```

