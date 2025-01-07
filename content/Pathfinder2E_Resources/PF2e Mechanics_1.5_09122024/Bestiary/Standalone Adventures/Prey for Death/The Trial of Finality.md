---
title: The Trial of Finality
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Adventure: Prey for Death
aliases: "Actor.joluBAPMZ9OE8ISO" 
level: 17
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "The Trial of Finality"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 33
sourcebook: "_Pathfinder Adventure: Prey for Death_"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A shaft of light shines from the ceiling to the floor in a ring of slowly churning smoke."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to use tools to reflect and focus the light shining from above into the surrounding smoke to disperse it and the hazard's magical energies, or [[Spells/Dispel Magic|Dispel Magic]] (9th rank; counteract DC 36) to counteract the trial"
attacks:
  - name: ""

  - name: "A Quick Death"
    desc: "`pf2:r` (incapacitation, mental, sleep) **Trigger** A living creature steps into the central 15-foot area of the room directly illuminated by light\n* * *\n\n**Effect** The triggering creature momentarily becomes convinced they have been dead for a long time, and that the events of this adventure are but a hallucination. If the triggering creature has come close to death earlier in this adventure, they briefly believe that they didn't actually survive that encounter. The creature must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The creature shakes off the conviction that they are dead and realizes it was a magically induced hallucination. The Trial of Finality deactivates.\n\n**Success** The creature becomes [[Conditions/Paralyzed|Paralyzed]], and the conviction that they are dead and now watching, as a ghost, their companions from the middle of the room. The Trial of Finality rolls initiative, and the creature remains paralyzed until the end of the hazard's next turn.\n\n**Failure** As success, but the creature becomes [[Conditions/Unconscious|Unconscious]] until the end of the trial's next turn instead of paralyzed. While unconscious, the creature experiences a dreamlike vision of being carried through the River of Souls toward the Boneyard, where their soul shall be judged.\n\n**Critical Failure** As failure, but the creature becomes [[Conditions/Doomed|Doomed 1]], or increases the value of an existing doomed condition by 1. If the creature dies as a result of this, the Trial of Finality deactivates."

  - name: "Routine"
    desc: "(1 or 2 actions; emotion, fear, mental) If a creature in area **B4** is [[Conditions/Paralyzed|Paralyzed]] or [[Conditions/Unconscious|Unconscious]] as a result of A Quick Death, the trial's first action is to Sustain that paralysis or unconscious effect; the paralyzed or unconscious creature can attempt a new DC 38 Will check save at this time against this effect with the same potential results as detailed above for A Quick Death, and the DC cumulatively decreases by 1 on each such save. The Trial of Finality's second action is to manifest horrifying ghostly shapes in the smoke that shriek and telepathically threaten everyone in area **B4**, promising them their deaths are imminent. All creatures other than the paralyzed or unconscious creature currently enduring A Quick Death must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature becomes [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature becomes [[Conditions/Frightened|Frightened 3]] and is [[Conditions/Fleeing|Fleeing]] as long as they remain frightened."
  - name: "Reset"
    desc: "Once the room is empty of living creatures, the trial deactivates and then resets after 1 minute has passed."
```

```encounter-table
name: The Trial of Finality
creatures:
  - 1: The Trial of Finality
```

