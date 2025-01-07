---
title: Flinging Tools
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.zwu0lLE3Vtg0Y597" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Flinging Tools"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 19
sourcebook: "_Pathfinder #202: Severed at the Root_"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Animated awls, hammers, nails, and other tools hurl themselves off the tool bench at intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Diplomacy check (master) to soothe the psychic echoes, DC 32 Religion check (expert) to overwhelm the area's energy, or DC 32 Occultism check (expert) to counter the psychic echoes; on the third successful check, the psychic echoes are disrupted, and the trap is destroyed."
attacks:
  - name: ""

  - name: "Tool Volley"
    desc: "`pf2:r` (attack) **Trigger** A living creature comes within 15 feet of the trap\n* * *\n\n**Effect** The trap makes a tool Strike against the triggering creature. The trap then rolls initiative."
  - name: "Melee"
    desc: "Tool +21 () no multiple attack penalty"

  - name: "Continuous Barrage"
    desc: "`pf2:0` **Trigger** A creature within 15 feet finishes an action\n* * *\n\n**Effect** The trap makes a tool Strike against the triggering creature."

  - name: "Routine"
    desc: "(1 action) The trap launches one tool against every living creature within 15 feet as 1 action. Because it flings tools continuously, the trap can also use the Continuous Barrage free action to fling tools at each creature during that creature's turn."
  - name: "Reset"
    desc: "The trap resets after 1 hour."
```

```encounter-table
name: Flinging Tools
creatures:
  - 1: Flinging Tools
```

