---
title: Paradox Engine
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Shadows at Sundown
aliases: "Actor.iJUauXDvyAoejBrh" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Shadows at Sundown"
name: "Paradox Engine"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 0
sourcebook: "_Pathfinder Adventure: Shadows at Sundown_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +22, "
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90; __Hardness__ 24; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 0" 
    desc: " +0"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "All six sides of this adamantine-reinforced box are covered with Thassilonian runes. Touching a rune allows one to exchange its position with another."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 41 Thievery check (expert) to feel the subtle vibrations when moving a rune to shift into the right position, or DC 33 Thassilon Lore check (expert) or DC 38 Society check (master) while being able to read Thassilonian to work out the anagram puzzle using traditional means, or [[Spells/Dispel Magic|Dispel Magic]] (7th rank; counteract DC 34)"
attacks:
  - name: ""

  - name: "Slicing Shadows"
    desc: "`pf2:r` (arcane) **Trigger** The paradox engine is damaged, or a creature fails a check to disable it\n* * *\n\n**Effect** Slats on the sides of the box open to release beams of razor-sharp freezing darkness that swipe throughout area **C5** and extend 10 feet south into area **C4**; all creatures in this area who lack the Shadow trait take 5d6 slashing damage and 5d6 cold damage (DC 34 Reflex check)."

  - name: "Routine"
    desc: "(3 actions) The slicing shadows congeal into the form of what appears to be the upper half of a skeletal, cowled humanoid: an [[Bestiary 3/Owb Prophet|Owb Prophet]]. This owb prophet is a creation of the paradox engine and does not have a forsaken patron. While the owb prophet is active, the paradox engine no longer uses its Slicing Shadows reaction; instead, the owb prophet focuses its attacks on creatures that attempt to damage or deactivate the engine. If the owb prophet is destroyed, the paradox engine's disable DCs and Hardness are reduced by 5. It thereafter functions as a simple hazard with the Slicing Shadows reaction, and resets after 1 round."
  - name: "Reset"
    desc: "The paradox engine deactivates 1 minute, and its owb prophet returns to its interior after all creatures leave the area, but resets immediately thereafter."
```

```encounter-table
name: Paradox Engine
creatures:
  - 1: Paradox Engine
```

