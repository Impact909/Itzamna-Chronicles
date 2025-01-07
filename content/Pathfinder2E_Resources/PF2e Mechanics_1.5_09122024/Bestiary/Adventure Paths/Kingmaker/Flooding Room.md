---
title: Flooding Room
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.vLWHACeJCkZEmohu" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Flooding Room"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 23
sourcebook: "_Pathfinder Kingmaker_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +23, __Ref__ +15, "
hp: 70
health:
  - name: ""
  - name: "HP"
    desc: "70; __Hardness__ 16; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "When the western secret door is opened or any of the trapdoors in the ceiling are forced open, the trap is triggered. As soon as this occurs, the portcullises to the east and west come crashing down, each consisting of solid iron sheets that form watertight seals. At the same time, the dozen 5-foot-wide trapdoors open in the ceiling. These holes are the mouths of winding tunnels that connect to a second pair of apertures on the submerged side of the island outside, allowing the waters of the Little Sellen River to plunge down into this room, possibly damaging or knocking [[Conditions/Prone|Prone]] those in the square portion of the room itself (but not in the adjoining hallway) and eventually flooding the entire chamber."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (this increases to DC 30 Thievery check once the trap is activated) to disable one of the 12 trapdoors and seal it shut; disabling all 12 of the trapdoors completely deactivates the trap, but a critical failure on any attempt causes the trap to trigger; DC 24 Thievery check to disable one of the watertight portcullises and prevent it from falling; magic such as shape stone or wall of stone or even lock can also be used to disable portions of this deadly trap at the GM's discretion"
attacks:
  - name: ""

  - name: "Rushing Water"
    desc: "`pf2:r` **Trigger** The secret door to the west or any trapdoor is opened.\n* * *\n\n**Effect** The 12 ceiling trapdoors open along with the two secret doors to the cyclops zombie alcoves, releasing river water and zombies into the room. Any creature standing in the central 40-by-40 foot section of the main room must attempt a DC 28 Reflex check save; the trap then rolls initiative.\n* * *\n\n**Critical Success** The creature takes no damage.\n\n**Success** The creature takes 1d10+6 bludgeoning damage from the cascade of water.\n\n**Failure** The creature takes 2d10+13 bludgeoning damage from the cascade of water.\n\n**Critical Failure** The creature takes 2d10+13 bludgeoning damage from the cascade of falling water and is knocked [[Conditions/Prone|Prone]]."

  - name: "Routine"
    desc: "(12 actions) The trap loses 1 action for each of its 12 ceiling trapdoors that are disabled. On each of the trap's actions, it pours water into the room, filling it to a depth of one inch. If all 12 trapdoors are open, it thus fills the room at a rate of 1 foot per round. If one of the portcullises is breached, the trap fills the room at half the rate, and if both are breached, it fills at one quarter the rate. Once the cascade of water begins, it's easy enough for a PC to avoid the downpour, but any creature that deliberately enters the cascade is subjected to the trap's Rushing Water reaction. If a creature is struck by Rushing Water while already underwater, the result of its Reflex save is automatically improved one degree of success.\n\nThe flooding ends and the trap deactivates once the area is filled to the ceiling-at this point, the water's surface is at the level of the river, and at the top of the stairs leading down from areas **D4** and **D6**. A Medium or smaller creature can try to Swim to freedom through one of the 5-foot-wide tunnels leading to the river from a trapdoor, but doing so requires navigating 200 feet of flooded tunnels."
  - name: "Reset"
    desc: "The trap must be reset with a major engineering effort."
```

```encounter-table
name: Flooding Room
creatures:
  - 1: Flooding Room
```

