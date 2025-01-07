---
title: Trial of the Gods
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder Adventure: Prey for Death
aliases: "Actor.0k13dob51hLiY1ic" 
level: 17
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Trial of the Gods"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 33
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, "
hp: 110
health:
  - name: ""
  - name: "HP"
    desc: "110; __Hardness__ 28; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "What appears to be an eye opens within the glowing orb near the ceiling."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to deactivate the glowing orb and prevent it from observing the room, [[Spells/Dispel Magic|Dispel Magic]] (9th rank; counteract DC 36) to counteract the trial, DC 45 Religion check (master) to perform a complex 5-round candle-lighting ritual, or placing General Ordulf's religious symbol on an empty hook on any wall as an Interact action"
attacks:
  - name: ""

  - name: "Wrath of the Gods"
    desc: "`pf2:r` (death, emotion, fear, illusion, mental) **Trigger** A creature attempts to [[Actions/Force Open|Force Open]] or [[Actions/Pick a Lock|Pick the Lock]] on the eastern door, or ends a turn in this room while not performing the candle-lighting ritual\n* * *\n\n**Effect** A glowing red eye manifests in the ceiling mounted orb to stare angrily at the triggering creature, who must succeed at a DC 46 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure). The Trial of the Gods then rolls initiative."

  - name: "Routine"
    desc: "(1 action; death, emotion, fear, mental) The red eye glances at a randomly determined creature in area **B3** that it can see and is not engaged in a candle-lighting ritual, then casts a 9th-rank [[Spells/Vision of Death|Vision of Death]] on that target, causing them to experience the sight of Achaekek rising up from the ground to smite the transgressor for failing to honor the gods."
  - name: "Reset"
    desc: "Once the room is empty of creatures, the trial deactivates and then resets after 1 minute has passed."
```

```encounter-table
name: Trial of the Gods
creatures:
  - 1: Trial of the Gods
```

