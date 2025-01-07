---
title: Test of Agility
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.J1OWIHT2tHDOirT6" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Test of Agility"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 27
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The floor of this circular room pivots and shifts awkwardly when weight is placed upon its surface, pitching those who attempt to walk on it off their feet and potentially into one of two deep spiked pits."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 37 Thievery check (expert) to wedge scraps of material into the edges of the room to hamper the floor's tilt (requires 4 successes)."
attacks:
  - name: ""

  - name: "Tilt and Roll"
    desc: "`pf2:r` **Trigger** A creature or object of at least 3 bulk moves onto the floor; the trap can use this reaction multiple times in a round, but only once per triggering creature or object\n\n**Effect** The floor pitches and rolls. The triggering creature must attempt a DC 33 Reflex check save.\n* * *\n\n**Critical Success** The character can move across the room normally this turn, without having to attempt Acrobatics checks, but treats the unstable floor as difficult terrain.\n\n**Success** The character treats the ground in this room as difficult terrain, but each time they move they must succeed at a DC 30 Acrobatics check check or they fall [[Conditions/Prone|Prone]] at the start of their turn. A character who falls prone must succeed at a DC 33 Reflex check save or fall into one of the two spiked pits to the north or south of the room (see Failure).\n\n**Failure** As success but the character automatically falls prone and must succeed at a DC 33 Reflex check save to avoid being pitched into one of the two spiked pits to the north or south of the room. A character who is pitched into a pit can attempt to [[Actions/Grab an Edge|Grab an Edge]] to avoid falling. The DC to Grab an Edge or [[Actions/Climb|Climb]] a pit's walls is 33. A character who falls into one of the pits plunges 50 feet onto a bed of spikes, taking 25 points of bludgeoning damage and 2d6 piercing damage (DC 33 Reflex check).\n\n**Critical Failure** As failure, but the character automatically rolls into one of the two pits."

  - name: "Routine"
    desc: "(1 action) On its initiative each turn, the floor tilts randomly, forcing all characters standing on the floor of the room to attempt a DC 33 Reflex check save to avoid being pitched into one of the two pits."
  - name: "Reset"
    desc: "This trap resets instantly."
```

```encounter-table
name: Test of Agility
creatures:
  - 1: Test of Agility
```

