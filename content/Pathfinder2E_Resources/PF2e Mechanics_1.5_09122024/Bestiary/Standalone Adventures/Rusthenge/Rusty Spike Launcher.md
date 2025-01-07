---
title: Rusty Spike Launcher
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: Rusthenge
aliases: "Actor.3ZYRsVPqzN6LwyoO" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Rusty Spike Launcher"
level: "Hazard 3"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder Adventure: Rusthenge_"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "As the large rusty door swings open, a mass of rusty spikes appear out of nowhere in the open doorway and launch violently into the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Thievery check to decouple the triggering rods that cause the spikes to extend, or [[Spells/Dispel Magic|Dispel Magic]] (2nd level; counteract DC 18) to counteract the trap"
attacks:
  - name: ""

  - name: "Launch Spikes"
    desc: "`pf2:r` **Trigger** a creature opens the door without uttering a prayer to Xar-Azmak first\n* * *\n\n**Effect** A mass of rusty spikes appears in the open doorway and then fire into area **E1**. The rusty spikes curve through the air to seek targets—all creatures in area **E1** must attempt a DC 20 Reflex check save.\n* * *\n\n**Critical Success** The creature avoids the spikes and takes no damage.\n\n**Success** A spike grazes the creature, inflicting 2d10 piercing damage.\n\n**Failure** A spike impales the creature, inflicting 2d10+13 piercing damage.\n\n**Critical Failure** As failure, but the spike also exposes the creature to tetanus."


  - name: "Reset"
    desc: "The trap automatically resets once the door is closed."
```

```encounter-table
name: Rusty Spike Launcher
creatures:
  - 1: Rusty Spike Launcher
```

