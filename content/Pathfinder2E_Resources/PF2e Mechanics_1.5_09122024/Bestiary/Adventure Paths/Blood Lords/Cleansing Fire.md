---
title: Cleansing Fire
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #185: A Taste of Ashes
aliases: "Actor.k3IxdJwobkvE2zm8" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #185: A Taste of Ashes"
name: "Cleansing Fire"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 43
sourcebook: "_Pathfinder #185: A Taste of Ashes_"
perception:
  - name: ""
  - name: "Stealth DC 43" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Sheets of fire and vitality energy blast through the room in waves that obliterate the undead and scorch the living."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 41 Thievery check (master) to bleed away the trap's energy, or DC 39 Religion check (expert) to recite the appropriate prayers to Urgathoa to stop the trap (Pesabnet knows these prayers and automatically succeeds at checks to recite them). Disabling the trap requires three successful checks, in any combination of Thievery and Religion checks."
attacks:
  - name: ""

  - name: "Holy Flame Burst"
    desc: "`pf2:r` (divine, fire, vitality) **Trigger** A creature tries to open the door to area **C6**\n* * *\n\n**Effect** Magical fire and vitality energy flood the room with a harmonious roar. All creatures in the room take 3d12 fire damage and 3d12 vitality damage and must attempt a DC 39 Reflex check save with the results below. The trap then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and 1d12 persistent fire damage.\n\n**Critical Failure** The creature takes double damage, 1d12 persistent fire damage, and 1d12 persistent vitality damage."

  - name: "Routine"
    desc: "(1 action) A wall of sacred fire washes back and forth throughout the room, bathing every inch of the space in holy power and dealing 3d12 fire damage 3d12 vitality damage. Each creature in the trap's area must attempt a DC 39 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes double damage.\n\n**Critical Failure** If the creature has void healing, it is instantly destroyed. Otherwise, it takes double damage and 1d12 persistent fire damage."
  - name: "Reset"
    desc: "The sacred fire disappears 1 minute after no creatures are in the room, and the trap immediately resets"
```

```encounter-table
name: Cleansing Fire
creatures:
  - 1: Cleansing Fire
```

