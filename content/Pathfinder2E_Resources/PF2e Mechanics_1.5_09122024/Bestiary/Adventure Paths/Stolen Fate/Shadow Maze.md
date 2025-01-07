---
title: Shadow Maze
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #191: The Destiny War
aliases: "Actor.SC6ygrIA2upsb2ex" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Shadow Maze"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 32
sourcebook: "_Pathfinder #191: The Destiny War_"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master) to realize the water within the dome poses a supernatural threat"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Shifting illusions disorient, entrap, and agonize those who attempt to pass through the shadowy maze."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Thievery check (master) to decouple faint strands of shadow essence from the magical matrix that holds the maze together, DC 45 Arcana check or DC 45 Occultism check to shunt the shadowy energy back into the Shadow Plane and render the maze inert, or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 35) to counteract the shadow maze"
attacks:
  - name: ""

  - name: "Disorient"
    desc: "action (illusion, incapacitation, mental) **Trigger** A creature enters the 20-foot-wide interior of the shadow maze, either from area **C2** or **C4**, or through a hole smashed in the dome\n* * *\n\n**Effect** Reality appears to shift around the creature, who perceives a sudden transformation in the surrounding terrain into a vast maze of underwater alleys and crumbling ruins. The creature must attempt a DC 37 Will check save, and the shadow maze then rolls initiative.\n* * *\n\n**Critical Success** The creature sees through the illusions and can move freely through squares within the shadow maze's effect. It's temporarily immune to the effects of the trap's routine for 1 minute.\n\n**Success** The creature understands that what it's experiencing is an illusion, but it isn't immune to the effects of the trap's routine.\n\n**Failure** The creature believes it has stepped into a vast maze. To those observing the creature outside of the shadow maze, the creature remains motionless. The creature becomes [[Conditions/Slowed|Slowed 2]] for 1 round, during which time all of its speeds are reduced to 5 feet.\n\n**Critical Failure** The creature not only believes it has entered a vast maze, but is overwhelmed with the sensation of being hopelessly lost. The creature is [[Conditions/Immobilized|Immobilized]] until the end of its next turn."

  - name: "Routine"
    desc: "(1 action; illusion, incapacitation, mental) The shadow maze shifts and adjusts its appearance, affecting all creatures currently located within its area. Any creatures in the area at this time must attempt a DC 37 Will check save.\n* * *\n\n**Critical Success** The creature sees through the illusions and can act normally.\n\n**Success** The creature treats all squares within the trap's area as difficult terrain, and the trap fills the creature's mind with sensations and false memories that it has been wandering these alleys for nearly an hour. The creature takes 5d6 mental damage from the perceived strain of navigating the alien flooded alleys.\n\n**Failure** As success, but the creature believes it has been wandering the alleys for several hours. It becomes [[Conditions/Slowed|Slowed 2]] for 1 round and takes 10d6 mental damage from the perceived strain.\n\n**Critical Failure** The creature believes it has been hopelessly lost in the alleys of the shadow maze for days, and it is incapacitated for 1 round and takes 20d6 mental damage from the perceived strain."
  - name: "Reset"
    desc: "If disarmed, the trap resets in 1 hour as long as the two crystals in area **C5** still function."
```

```encounter-table
name: Shadow Maze
creatures:
  - 1: Shadow Maze
```

