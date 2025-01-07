---
title: Quarry Sluiceway
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #147: Tomorrow Must Burn
aliases: "Actor.juERNiuA9cJei2uJ" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Quarry Sluiceway"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert) or DC 27 Perception check (expert) to notice the six cleverly hidden sluice gates while they are closed"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Six sluice gates open to allow thousands of gallons of water to begin flooding the room. The water churns through the room and flows out through three chutes on the south end of the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (expert) twice to close a sluice (on a critical success, a sluice is closed immediately)"
attacks:
  - name: ""

  - name: "Opened Sluices"
    desc: "`pf2:r` **Trigger** A creature [[Actions/Interact|Interacts]] to throw either the primary lever or backup lever.\n* * *\n\n**Effect** The trap rolls initiative."

  - name: "Routine"
    desc: "(6 actions) The trap loses 1 action per disabled or destroyed sluice. On each of its actions, the water rushing from the sluices flows through the room, creating a river of churning water that fills the room to several inches and makes the floor of the chamber into difficult terrain. The water level never rises above this level in the room, as it drains out of the chutes to the south and begins to flood the quarry pit (area **J2**). On the trap's second turn, the water starts filling the four slave pits in area **J2**. Each of the trap's actions fills the pits 4 inches (2 feet per round if all sluices are functional). If the slave pits fill to their total depth of 12 feet and the grates over the slave pits aren't open, the slaves begin to drown, dying if they aren't freed in 5 rounds. Once the slave pits are full, the water continues to slowly fill the central area over the course of an hour until it empties the reservoir and floods area **J2** to a depth of 15 feet.\n\nOther options beyond disabling or destroying the sluices could prevent the flooding of the quarry pit at your discretion."
  - name: "Reset"
    desc: "The trap resets if all six sluices are closed. If all the water has drained when this occurs, the water takes many months to refill."
```

```encounter-table
name: Quarry Sluiceway
creatures:
  - 1: Quarry Sluiceway
```

