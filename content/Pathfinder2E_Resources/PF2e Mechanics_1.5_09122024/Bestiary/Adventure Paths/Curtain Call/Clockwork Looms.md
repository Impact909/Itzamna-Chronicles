---
title: Clockwork Looms
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #205: Singer, Stalker, Skinsaw Man
aliases: "Actor.5tzVtQaRzOcLReJs" 
level: 13
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #205: Singer, Stalker, Skinsaw Man"
name: "Clockwork Looms"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 27
sourcebook: "_Pathfinder #205: Singer, Stalker, Skinsaw Man_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +20, "
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90; __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The looms spring to life, sending skeins of spidersilk yarn between them that attempt to ensnare nearby creatures and pull them into the machinery."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 46 Thievery check (master) to shut down all eight looms at once by activating either of the bypass locks once either lock is located (this check is automatically successful if Fenton's keys are used), DC 37 Thievery check (master) twice to shut down a single loom by deftly removing critical components, or [[Spells/Dispel Magic|Dispel Magic]] (7th rank, counteract DC 33) to counteract a single loom"
attacks:
  - name: ""

  - name: "Weaving Clatter"
    desc: "`pf2:r` **Trigger** A Small or larger creature ends their turn in area **C6**\n* * *\n\n**Effect** The looms suddenly begin to grind and churn, filling the room with the squeal of metal on metal. All eight looms roll initiative."

  - name: "Routine"
    desc: "(1 action) Each loom takes one of two possible actions on its turn, depending on if it's currently restraining a creature or not.\n\n**Not Restraining a Creature:** If a loom isn't restraining a creature, it launches a tangle of yarn at a random creature in the room that isn't currently [[Conditions/Restrained|Restrained]]. That creature must attempt a DC 37 Reflex check save. If there are no non-restrained targets for the loom to attempt to grapple, it takes no actions this round.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is entangled, and becomes [[Conditions/Clumsy|Clumsy 1]] until the end of the looms' next turn.\n\n**Failure** The creature is tangled in the yarn and becomes [[Conditions/Clumsy|Clumsy 2]] until the end of the loom's next turn—or if it already has the clumsy condition, it becomes restrained (see critical failure).\n\n**Critical Failure** The creature becomes restrained. A restrained creature can [[Actions/Force Open|Force Open]] the tangle of yarn or [[Actions/Escape|Escape]] with a DC 37 check.\n\n**Restraining a Creature:** If a loom has restrained a creature, it instead fires more lines of yarn at the restrained creature and then drags that creature (if the creature is Medium or smaller) 20 feet toward itself. (If it's restraining a Large or larger creature, it can only drag the creature 5 feet toward itself). If this dragging causes a creature to become adjacent to the loom, the loom pulls the creature into its grinding gears and inflicts 5d12 bludgeoning + 5d12 slashing damage to the creature (DC 37 Reflex check save). The creature is then placed in an adjacent square and is still restrained by that loom."
  - name: "Reset"
    desc: "A loom deactivates if no Small or larger creatures are in area **C6**, resetting in 1 minute unless disabled or all looms are broken."
```

```encounter-table
name: Clockwork Looms
creatures:
  - 1: Clockwork Looms
```

