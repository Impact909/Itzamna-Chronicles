---
title: Rolling Stone Cylinder Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #194: Cult of the Cave Worm
aliases: "Actor.7tQKqftlQdvF0zwr" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Rolling Stone Cylinder Trap"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +18, __Ref__ +11, "
hp: 58
health:
  - name: ""
  - name: "HP"
    desc: "58,  (BT 29); __Hardness__ 14; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 10-foot-long, 5-foot-thick column of stone thuds to the ground, just in front of the bridge. It immediately starts to roll down the bridge, quickly picking up speed."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Thievery check check to create a wedge to immobilize the column, DC 21 Athletics check check to immobilize the column until the end of the creature's next turn, a creature can Climb over an [[Conditions/Immobilized|Immobilized]] column with a successful DC 18 Athletics check check."
attacks:
  - name: ""

  - name: "Drop and Roll"
    desc: "`pf2:r` A lever at the top of the south tower is pulled\n* * *\n\n**Effect** A thick column of stone drops from above the gate, then uses crushing roll. The rolling stone cylinder trap rolls initiative."

  - name: "Speed 20 feet (west only)"
    desc: "passive "

  - name: "Crushing Roll"
    desc: "action **Requirements** The rolling stone cylinder is not [[Conditions/Immobilized|Immobilized]]\n* * *\n\n**Effect** The rolling stone cylinder trap moves its Speed west along the bridge. Creatures it moves past or lands on take 5d6 bludgeoning damage and are forced to move west to the first available space (DC 27 Reflex check). Creatures who critically succeed at the Reflex save are not damaged but are still moved west. If the rolling stone tries to move into a non-creature obstruction, such as a wall or barricade, it deals bludgeoning damage to the obstruction and only continues moving if the obstruction is destroyed, otherwise the trap stops."

  - name: "Routine"
    desc: "(1 action) The rolling stone cylinder trap uses Crushing Roll."

```

```encounter-table
name: Rolling Stone Cylinder Trap
creatures:
  - 1: Rolling Stone Cylinder Trap
```

