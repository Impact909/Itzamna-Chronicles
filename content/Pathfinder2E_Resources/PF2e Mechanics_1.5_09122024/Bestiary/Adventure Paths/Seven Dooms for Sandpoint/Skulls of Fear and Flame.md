---
title: Skulls of Fear and Flame
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.1xrPyRAfx5qd6DpM" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Skulls of Fear and Flame"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +12, "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10, Skulls; __Hardness__ 14; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert) to notice little wisps of smoke start to curl up from the unlit candles on the skulls."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A line of skulls adorned with black candles sit on the floor, and use darkvision to spot intruders. The red arrows on the map indicate the direction the skulls are looking."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Stealth check to move through the room unseen by the skulls (this does not disable the trap but does prevent it from triggering), DC 27 Thievery check three times to \"blind\" an adjacent skull by deftly scraping hidden runes away from the inside of the eye sockets, or [[Spells/Dispel Magic|Dispel Magic]] (4th level, counteract DC 25) to counteract the trap"
attacks:
  - name: ""

  - name: "Fearful Cry"
    desc: "`pf2:r` (arcane, emotion, fear) **Trigger** A creature walks into view of the skulls and is spotted by them\n* * *\n\n**Effect** The candles atop all six skulls flare to light and the skulls shriek out fearsome, mind-numbing howls. All creatures in area **F6**, the stairs, or the eastern trough must attempt a DC 25 Will check save. The trap then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Fleeing|Fleeing]] as long as they remain frightened.\n\n**Critical Failure** As failure, but once the creature is no longer frightened, the previous minute of memories are erased—likely removing knowledge of the secret door at the top of the stairs in area **E7a**. All that remains are strange lingering fears about returning to the area."
  - name: "Melee"
    desc: "Fire Beam +18 (fire, range 25 feet) "

  - name: "Routine"
    desc: "(6 actions) On its initiative the trap uses its first action to rotate a skull that can't see targets a full 360 degrees, stopping as soon as the skull spots a target. It repeats this action until all six skulls are looking at targets, then uses its remaining actions to shoot beams of fire from their eyes. The trap can only target a creature once per round, so if there are fewer targets than actions, any additional actions possessed by the trap are lost. The trap loses one action for each skull that is destroyed."
  - name: "Reset"
    desc: "If there are no visible targets, the trap deactivates at the end of its turn, then automatically resets."
```

```encounter-table
name: Skulls of Fear and Flame
creatures:
  - 1: Skulls of Fear and Flame
```

