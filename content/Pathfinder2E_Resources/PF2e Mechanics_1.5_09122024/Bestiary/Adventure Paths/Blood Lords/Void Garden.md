---
title: Void Garden
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.3Mciu250aRUGj87Y" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Void Garden"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 28
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +22, "
hp: 92
health:
  - name: ""
  - name: "HP"
    desc: "92, Per crystal; __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 15"
perception:
  - name: ""
  - name: "Stealth DC 28" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Six eerie purple crystals react to the presence of life, pulsing with flashes of violet light that seem to match the heartbeats of living creatures in the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) or DC 35 Nature check (master) to discern a hairline fracture that, when struck, shatters a crystal to dust"
attacks:
  - name: ""

  - name: "Negative Energy Pulse"
    desc: "`pf2:r` (attack) **Trigger** A living creature enters the circular portion of area **D4**, or a crystal takes damage from any source\n* * *\n\n**Effect** The void garden creates a pulse of void energy that fills the entire room and, if the doors to area **D3** are open, extends 30 feet into the hallway beyond. All living creatures in this area must attempt a DC 34 Fortitude check save. The trap then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected\n\n**Success** The creature takes 5d6 void damage.\n\n**Failure** The creature takes 8d6 void damage and is [[Conditions/Drained|Drained 1]].\n\n**Critical Failure** The creature takes 16d6 void damage and is [[Conditions/Drained|Drained 2]]."
  - name: "Melee"
    desc: "Void Ray +29 (range 120 feet, void) Plus [[Conditions/Drained|Drained 1]] (this drained value stacks with that caused by other void rays or the hazard's Negative Energy Pulse, to a maximum of [[Conditions/Drained|Drained 5]])."

  - name: "Routine"
    desc: "(6 actions) The void garden's crystals each use an action to fire a void ray, a beam of destructive dark purple energy, at a random living creature in the room or in visible reach through the open doorway (the crystals don't fire at living targets on the balcony in area **D6c**). A single creature can be targeted only once per round by a void ray. The void garden loses one action for each crystal that is disarmed or destroyed."
  - name: "Reset"
    desc: "The void garden deactivates 1 round after all living targets leave the area but resets immediately thereafter."
```

```encounter-table
name: Void Garden
creatures:
  - 1: Void Garden
```

