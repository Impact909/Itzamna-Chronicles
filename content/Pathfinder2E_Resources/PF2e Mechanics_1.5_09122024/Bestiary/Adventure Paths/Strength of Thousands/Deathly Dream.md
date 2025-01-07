---
title: Deathly Dream
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #173: Doorway to the Red Star
aliases: "Actor.LTEteYVs0NTKqPYR" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Deathly Dream"
level: "Hazard 15"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 28
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +29, __Ref__ +23, "
hp: 96
health:
  - name: ""
  - name: "HP"
    desc: "96; __Hardness__ 24; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 38" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Sinister runes adorn the doorway, opening a portal to a realm of nightmares if anyone other than Dwandek opens the door."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Thievery check (master) to seal the rift using materials strongly grounded to the Material Plane, or [[Spells/Dispel Magic|Dispel Magic]] (7th‑level, counteract DC 33) to counteract the portal."
attacks:
  - name: ""

  - name: "Drawn to Nightmare"
    desc: "`pf2:r` (arcane, teleportation) **Trigger** A creature other than Dwandek opens the door\n* * *\n\n**Effect** The triggering creature is drawn into a pocket plane of pure nightmare (DC 38 Will check save to resist). Each round at the start of their turn, the creature takes 4d8 mental damage as they are assaulted by otherworldly visions, and must succeed at a new Will save against the original DC to be ejected from the pocket plane and deposited in the center of area **A5**."


  - name: "Reset"
    desc: "The deathly dream trap resets automatically as long as it hasn't been disabled or destroyed. Each time it resets, the tiny pocket plane of nightmare it sends its victim into resets as well, so no two victims will ever share the same deathly dream."
```

```encounter-table
name: Deathly Dream
creatures:
  - 1: Deathly Dream
```

