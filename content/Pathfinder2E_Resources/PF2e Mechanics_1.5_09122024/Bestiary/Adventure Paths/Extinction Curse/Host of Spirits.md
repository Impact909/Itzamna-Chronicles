---
title: Host of Spirits
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #155: Lord of the Black Sands
aliases: "Actor.BgTE42pKU2rasXSp" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Host of Spirits"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 35
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
perception:
  - name: ""
  - name: "Stealth DC 35" 
    desc: "+35 (expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A host of angry spirits inhabiting the ruined house attempts to drag living creatures closer and crush them to death."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Religion check (master) to exorcise the spirits or DC 45 Deception check (master) to trick the spirits into departing"
attacks:
  - name: ""

  - name: "Embrace of Death"
    desc: "`pf2:r` (attack, death, occult) **Trigger** A creature that has angered the haunt begins its turn within 50 feet of the ruins of the house\n* * *\n\n**Effect** The haunt attempts a ghostly hand Strike against the target creature, and then rolls initiative."
  - name: "Melee"
    desc: "Ghostly Hand +35 () "

  - name: "Ghostly Grip"
    desc: "passive A creature outside the house that takes damage from the host of spirits' ghostly hand Strike must succeed at a DC 42 Reflex check save or be pulled directly into the house. If there is a wall in the creature's path, that section of wall is destroyed, and the creature takes an additional 3d12 bludgeoning damage. The haunt's ghostly hand Strike also deals an additional 6d6 bludgeoning damage to a target already inside the house (DC 42 Fortitude check save)."

  - name: "Routine"
    desc: "`pf2:3` For each of its actions, the trap attempts a ghostly hand Strike against a different creature within 50 feet of the ruins of the house (if there are fewer than 3 creatures, the haunt doesn't use its remaining actions)."
  - name: "Reset"
    desc: "The haunt ends 1 round after no creatures are within 50 feet of the house. The haunt resets after 1 day."
```

```encounter-table
name: Host of Spirits
creatures:
  - 1: Host of Spirits
```

