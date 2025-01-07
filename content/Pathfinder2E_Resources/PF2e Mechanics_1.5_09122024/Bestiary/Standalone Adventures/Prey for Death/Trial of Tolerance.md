---
title: Trial of Tolerance
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Adventure: Prey for Death
aliases: "Actor.nIy0cDbnzX7iHCAi" 
level: 17
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Trial of Tolerance"
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
    desc: "A convincing illusion of a bustling market scene fills the empty room, confronting the viewers with potentially frightening diversity and unexpected encounters."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to scratch out well-hidden key runes etched into the room's floor, or [[Spells/Dispel Magic|Dispel Magic]] (9th rank; counteract DC 36) to counteract the trial"
attacks:
  - name: ""

  - name: "Unveil the Bazaar"
    desc: "`pf2:r` (illusion, mental) **Trigger** A creature begins its turn in area **B2**\n* * *\n\n**Effect** A convincing illusion of an Ilizmagorti city bazaar appears, complete with a cloudless blue sky above. The surrounding crowd is dense, and the smells and sights and sounds are quite realistic even as no one in the crowd actually bumps against the PCs as they mill about. The Trial of Tolerance then rolls initiative."

  - name: "Reflective Violence"
    desc: "`pf2:r` (illusion, mental) **Trigger** A creature uses a hostile action against an illusory figure created by the Trial of Tolerance or fails at an attempt to disable the trap\n* * *\n\n**Effect** The illusory figure effortlessly avoids the triggering action, then appears to attack the triggering creature using its most harrowing and violent option. Regardless of what this attack appears as, the triggering creature takes 3d12+19 mental damage (DC 38 Reflex check save)."

  - name: "Routine"
    desc: "(1 action; emotion, fear, illusion, mental) An unexpectedly aggressive or frightening looking figure, such as a Hellknight, demon, pirate, or cloaked assassin suddenly emerges from the crowd and quickly advances toward a randomly determined character in the room, then stands menacingly in their path until the end of the round before they appear to lose interest and drift back into the crowd. If the target has a type of fear or hatred toward a specific kind of creature, this unexpected figure epitomizes those fears and hatreds. The target must succeed at a DC 46 Will check save or become [[Conditions/Frightened|Frightened 1]] (or [[Conditions/Frightened|Frightened 2]] on a critical failure). If any creature in the room takes any hostile action against the intimidating figure, the Trial of Tolerance uses its Reflective Violence reaction. Once three rounds pass without the Trial of Tolerance using Reflective Violence, the hazard deactivates."
  - name: "Reset"
    desc: "Once the room is empty of creatures, the trial deactivates and then resets after 1 minute has passed."
```

```encounter-table
name: Trial of Tolerance
creatures:
  - 1: Trial of Tolerance
```

