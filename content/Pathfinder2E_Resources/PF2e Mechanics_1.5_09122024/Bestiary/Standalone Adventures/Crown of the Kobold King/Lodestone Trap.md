---
title: Lodestone Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Crown of the Kobold King
aliases: "Actor.mSTtWaScxqK9dNhA" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Lodestone Trap"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: -2
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +5, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30, BT 15; __Hardness__ 8; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC -2" 
    desc: " -2"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The magical lodestone discharges bolts of electricity that also magnetize metal in the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check to unhook the pressure plates from the trap, or [[Spells/Dispel Magic|Dispel Magic]] (2nd level, counteract DC 18) to counteract the trap"
attacks:
  - name: ""

  - name: "Magneto-Electric Pulse"
    desc: "`pf2:r` **Trigger** A single Medium or two or more Small creatures end their turn inside the room.\n\n**Effect** A pulse of electricity discharges from the lodestone to strike all four doors, with smaller arcs of electricity lancing out to strike all creatures in the room. The south and east doors slam shut, while the north and west doors fly open, releasing two vargouilles into the room. All creatures in the room take 2d6 electricity damage (DC 18 Reflex check). The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action) On its initiative, the trap exerts a strong magnetic pull on the doors, causing the north and west doors to open if they're closed, or causing the south and east doors to close if they're open. A character can open or close a door against this pull with a successful DC 18 Athletics check check to [[Actions/Force Open|Force Open]] the door. At the same time, any character in the room who wears primarily metal armor must attempt a DC 18 Reflex check save (characters in medium metal armor suffer a -1 circumstance penalty to this save, and characters in heavy metal armor suffer a -2 circumstance penalty).\n* * *\n\n**Critical Success** The PC is unaffected.\n\n**Success** The PC resists the pull but treats the room as difficult terrain.\n\n**Failure** The PC treats the room as difficult terrain and is knocked [[Conditions/Prone|Prone]]. A PC who's already prone suffers a critical failure instead.\n\n**Critical Failure** As failure, but the PC is also pulled 5 feet toward the lodestone. A PC who is adjacent to the lodestone instead becomes stuck to it and is [[Conditions/Restrained|Restrained]] as long as the trap continues its routine (escape DC 18)."
  - name: "Reset"
    desc: "At the end of a round in which there are no creatures standing on the floor or stuck to the lodestone, the trap deactivates. The vargouilles return to their alcoves, and the doors close. The trap resets automatically after 1 minute."
```

```encounter-table
name: Lodestone Trap
creatures:
  - 1: Lodestone Trap
```

