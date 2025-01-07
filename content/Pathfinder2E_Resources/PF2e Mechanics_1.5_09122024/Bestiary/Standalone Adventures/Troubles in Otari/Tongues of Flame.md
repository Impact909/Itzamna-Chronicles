---
title: Tongues of Flame
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Troubles in Otari
aliases: "Actor.wFz1EOb5ZcR4eLjr" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Troubles in Otari"
name: "Tongues of Flame"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder Adventure: Troubles in Otari_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +8, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, to destroy a single nozzle; &lt;strong&gt;Door&lt;/strong&gt; Hardness 6,  &lt;strong&gt;HP&lt;/strong&gt;  22 (BT 11) to break open a door and escape the hallway; __Hardness__ 12; __Immunities__  object immunities,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: " +13"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Nozzles hidden in the ceiling of the four corridors leading to the intersection spray jets of flame along their lengths when the trap is triggered."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Thievery check to disable a single nozzle, DC 21 Thievery check twice to unlock a door, or DC 25 Thievery check to deactivate the trap from the control panel. A hero who isn't trained in Thievery automatically fails these checks."
attacks:
  - name: ""

  - name: "Seal the Doors"
    desc: "`pf2:r` If a creature enters the corridor intersection, the four doors exiting this intersection close and lock, and the trap rolls Stealth (+13) for its initiative."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action each turn for each disabled nozzle. On each action, a different nozzle fires a jet of flame down a different corridor, dealing 3d6 fire damage to each creature in the first 10 feet of the corridor past the intersection (DC 22 Reflex check).\n\nA creature standing in the corridor intersection can be hit by only one flame jet per round even if they're in the area of multiple flame jets. The creature attempts only one saving throw per round, but it takes a -2 circumstance penalty to its saving throw."
  - name: "Reset"
    desc: "The trap deactivates and resets after 10 minutes. After the trap is activated for the fourth time, it runs out of fuel and must be reset manually."
```

```encounter-table
name: Tongues of Flame
creatures:
  - 1: Tongues of Flame
```

