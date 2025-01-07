---
title: Electrified Water Ward
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #170: Spoken on the Song Wind
aliases: "Actor.ALqkWKjzk5BVJShi" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #170: Spoken on the Song Wind"
name: "Electrified Water Ward"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 18
sourcebook: "_Pathfinder #170: Spoken on the Song Wind_"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Passing over an invisible rune on the floor between the north and south doors triggers a dancing burst of electricity."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (expert), DC 28 Arcana check (expert), or DC 28 Occultism check (expert) to harmlessly bleed away the electrical energy from the rune. Once the trap has been activated, the electrical energy is stronger, so three successful checks (of any combination of the relevant skills) are necessary to deactivate it, but these checks can be attempted from anywhere in the room."
attacks:
  - name: ""

  - name: "Electrocution"
    desc: "`pf2:r` (arcane, electricity) **Trigger** A creature passes over the invisible underwater rune between the north and south doors\n* * *\n\n**Effect** The trap deals 4d10 electricity damage (DC 26 Reflex check save) to creatures touching the water, and then rolls initiative."

  - name: "Routine"
    desc: "(1 action) The trap deals 4d10 electricity damage (DC 26 Reflex check save) to all creatures in the room. A creature that fails the save is [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). A creature that isn't touching the water treats the result of its saving throw as one degree of success better."
  - name: "Reset"
    desc: "The pulses stop as soon as no creatures are in the hallway, and then reset after 1 hour."
```

```encounter-table
name: Electrified Water Ward
creatures:
  - 1: Electrified Water Ward
```

