---
title: Vengeful Furnace
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #163: Ruins of Gauntlight
aliases: "Actor.X1GhjlzgFpGjaIlR" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Vengeful Furnace"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 15
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +8, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Hardness__ 13; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ cold 8, vitality 5"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The hatch atop the haunted furnace flips open and disgorges a pair of shrieking, burning ghosts."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Intimidation check (trained) to cow one of the vengeful spirits or DC 25 Religion check (trained) to exorcise the spirit. The haunt remains active until both spirits are cowed or exorcised, or until the furnace is destroyed."
attacks:
  - name: ""

  - name: "Burn Knowledge"
    desc: "passive (divine, fire, mental) The target of the haunt's initial Ghostly Assault, as well as any creature later hit by a burning lash Strike, loses random memories, as if these thoughts were incinerated like pages in a burning book.\n\nThe creature must attempt a DC 23 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Stupefied|Stupefied 1]] for 1 minute while they forget random memories, as if these thoughts were incinerated like pages in a burning book.\n\n**Failure** As success, but the stupefied 1 condition persists for 24 hours.\n\n**Critical Failure** As failure, but [[Conditions/Stupefied|Stupefied 2]]."
  - name: "Melee"
    desc: "Burning Lash +14 (fire, mental, range increment 10 feet) "

  - name: "Ghostly Assault"
    desc: "`pf2:r` (divine, fire, mental) **Trigger** A living creature with an Intelligence score of 15 or higher enters the room, or any creature touches the furnace\n* * *\n\n**Effect** Burning ghosts burst from the furnace, exposing the triggering creature to the haunt's burn knowledge effect. The haunt rolls initiative."

  - name: "Routine"
    desc: "(3 actions) The burning ghosts lash at a random [[Conditions/Stupefied|Stupefied]] creature in the room (or any random creature, if no creatures in the room are stupefied)."
  - name: "Reset"
    desc: "The haunt resets 1 hour after there are no creatures in the room."
```

```encounter-table
name: Vengeful Furnace
creatures:
  - 1: Vengeful Furnace
```

