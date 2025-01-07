---
title: Distortion Circle
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #205: Singer, Stalker, Skinsaw Man
aliases: "Actor.XtFTzlhvkscYmjnu" 
level: 19
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Distortion Circle"
level: "Hazard 19"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 37
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
perception:
  - name: ""
  - name: "Stealth DC 37" 
    desc: "(expert) to notice the softly glowing magic circle shimmering from under the moldering sheets; noticing the circle if the sheets are pulled aside has a DC of 0"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A softly flickering circle of runes pulses and periodically distorts the air above it before a raw red wound in reality splits open to disgorge demons and lash out with tendrils of acidic blood."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 47 Thievery check to erase key runes from the circle, defeat all four summoned demons in combat, or [[Spells/Dispel Magic|Dispel Magic]] (9th rank, counteract DC 36)"
attacks:
  - name: ""

  - name: "Summon Demons"
    desc: "`pf2:r` (arcane) **Trigger** A creature approaches within 10 feet of the distortion circle\n* * *\n\n**Effect** The distortion circle begins glowing with red light, shining through any cloth covering it might still have over it, and then summons four seraptis demons into the room. The demons appear in pairs at the entrances to the alcoves to the left and right of the distortion circle's alcove, and they then roll initiative. The demons do not pursue foes from this room, and vanish if the trap resets or if the trap is disabled. The summoned demons can use 3 actions each round and can use reactions, unlike most summoned creatures. The distortion circle then appears to open into a bloody toothy mouth and rolls initiative."
  - name: "Melee"
    desc: "Tooth Volley +33 (magical, range 90 feet) "

  - name: "Routine"
    desc: "(1 action) On its initiative, the trap extends a tongue-like appendage covered with sharp teeth. The tongue snaps like a whip, firing a volley of sharp teeth at a non-demon target in the room. The trap can precisely sense the location of all viable targets in the room, and teeth fired from the tongue penetrate the many wooden shelves (although a character with at least one shelf between it and the trap gains greater cover)."
  - name: "Reset"
    desc: "The distortion circle deactivates (and any summoned demons vanish) at the end of any round in which no viable targets for the tongue to attack are in area **C10**. The trap then immediately resets (and is ready to summon a new batch of four demons)."
```

```encounter-table
name: Distortion Circle
creatures:
  - 1: Distortion Circle
```

