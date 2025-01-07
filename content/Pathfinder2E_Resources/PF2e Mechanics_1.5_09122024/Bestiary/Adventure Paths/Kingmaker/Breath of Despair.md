---
title: Breath of Despair
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.bxUfJaYSMrJDO4mG" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Breath of Despair"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder Kingmaker_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +9, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30, HP for each face, 4 faces; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The faces carved on the wall appear to inhale, then exhale slithering tendrils of darkness to harm those who would despoil the tomb."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Thievery check (expert) to disarm the trap's sensors in the chamber floor, or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 23) to counteract the faces. Breaking one of the faces on the walls reduces the trap's save DC, attack rolls, and its total actions by 1 per broken face; if all four faces are destroyed, the trap is disabled."
attacks:
  - name: ""

  - name: "Draining Inhalation"
    desc: "`pf2:r` (divine) **Trigger** A non-flying living creature moves more than 10 feet into the area\n\n**Effect** Each face inhales then exhales, and all living creatures in the area feel their strength and vitality being drawn out of them as tendrils of shadow from the faces latch onto their bodies. Each creature must succeed at a DC 22 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 1]] ([[Conditions/Enfeebled|Enfeebled 2]] on a critical failure)."
  - name: "Melee"
    desc: "Despairing Breath +17 (fear, mental) No multiple attack penalty. A creature damaged by the despairing breath must succeed at a DC 22 Will check save or become [[Conditions/Frightened|Frightened 1]] (or [[Conditions/Fleeing|Fleeing]] 1 on a critical failure); this effect has the fear trait."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action per disabled face each turn. On each action, a different face spews a writhing breath of darkness from its mouth to a target in the area. A creature can only be targeted once per round by the despairing breath, so if fewer than four creatures are in the room, the trap won't be able to take full advantage of all four of its actions."
  - name: "Reset"
    desc: "The trap resets after 1 minute"
```

```encounter-table
name: Breath of Despair
creatures:
  - 1: Breath of Despair
```

