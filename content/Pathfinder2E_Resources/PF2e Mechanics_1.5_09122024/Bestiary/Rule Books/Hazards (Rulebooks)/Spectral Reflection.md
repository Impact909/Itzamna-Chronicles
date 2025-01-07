---
title: Spectral Reflection
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard

  - remaster
source: Pathfinder GM Core
aliases: "Actor.Ac9yxCqiA0bgZLXz" 
level: 5
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Spectral Reflection"
level: "Hazard 5"


trait_01: [[haunt]]
modifier: 16
sourcebook: "_Pathfinder GM Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +15, __Ref__ +10, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 13; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 26" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The reflection in the mirror subtly twists and distorts, its expression taking on an unnerving sneer of malice."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Religion check (trained) to exorcise the spirit, or DC 23 Thievery check (trained) to quickly cover the mirror"
attacks:
  - name: ""

  - name: "Spectral Impale"
    desc: "`pf2:r` **Trigger** A living creature approaches within 15 feet of the mirror, and the mirror is lit with dim or brighter light.\n* * *\n\n**Effect** Shadowy barbs impale the body of the reflected creature as the haunt makes a shadow barbs Strike."
  - name: "Melee"
    desc: "Shadow Barbs +19 () "

  - name: "Sap Vitality"
    desc: "passive A creature hit by the reflection's shadow barbs must attempt a DC 22 Fortitude check save as the haunt tries to draw a portion of its vital essence into the mirror. The target is [[Conditions/Drained|Drained 1]] on a failed saving throw, or [[Conditions/Drained|Drained 2]] on a critical failure."

  - name: "Special"
    desc: "passive Spectral reflections often infuse entire buildings, manifesting in any sufficiently large mirror. The example Hit Points and Hardness given represent a typical mirror reinforced by the haunt; at your discretion, the haunt might appear in reflective surfaces that are harder to destroy. Defeating a manifestation through damage destroys the surface, preventing the haunt from using it again. If this haunt appears in an area with many mirrors, consider giving PCs double or even triple the XP for a typical simple hazard."


  - name: "Reset"
    desc: "The haunt re-forms after 1 minute, manifesting in any mirror within its infused area (see Special below)."
```

```encounter-table
name: Spectral Reflection
creatures:
  - 1: Spectral Reflection
```

