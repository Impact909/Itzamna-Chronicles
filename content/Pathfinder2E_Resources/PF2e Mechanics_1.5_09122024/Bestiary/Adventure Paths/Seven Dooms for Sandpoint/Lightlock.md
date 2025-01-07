---
title: Lightlock
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.k9zXrHAd7nY46g8X" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Lightlock"
level: "Hazard 7"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
perception:
  - name: ""
  - name: "Stealth DC 25" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The strange fog layer on the walls swirls and churns, then suddenly fires several beams of dark mist into the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Thievery check (master) to disrupt some of the hidden runes that focus the trap's energies, or [[Spells/Dispel Magic|Dispel Magic]] (4th level, counteract DC 25) or any spell with the Light trait to counteract the trap"
attacks:
  - name: ""

  - name: "Freeze the Awful Light"
    desc: "`pf2:r` (cold, darkness) **Trigger** A creature carrying a light source ends their turn in area **F8**\n* * *\n\n**Effect** The walls fire beams of chilling dark fog at the triggering creature, who takes 10d6 cold damage (DC 25 Fortitude check save). The beams also attempt to counteract any light source the triggering creature carries. Non-magical light sources of 7th level or less are automatically extinguished. Against other light sources, the lightlock casts a 4th-rank [[Spells/Dispel Magic|Dispel Magic]] spell with a counteract modifier of +14 to attempt to counteract the light."


  - name: "Reset"
    desc: "The lightlock takes 1 minute to restore its energy, after which it can be triggered again."
```

```encounter-table
name: Lightlock
creatures:
  - 1: Lightlock
```

