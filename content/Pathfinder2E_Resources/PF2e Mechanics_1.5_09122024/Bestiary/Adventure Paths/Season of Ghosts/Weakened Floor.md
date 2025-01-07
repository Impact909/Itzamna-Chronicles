---
title: Weakened Floor
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #199: To Bloom Below the Web
aliases: "Actor.FJ0c2G2p0Ht8e5KB" 
level: 11
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #199: To Bloom Below the Web"
name: "Weakened Floor"
level: "Hazard 11"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 23
sourcebook: "_Pathfinder #199: To Bloom Below the Web_"
perception:
  - name: ""
  - name: "Stealth DC 23" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The weakened floor gives way with a tremendous crash, dropping everything in the room into a muddy morass of toxic mold."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Crafting check (master) three times to knock holes in the floor without triggering the spore cloud while simultaneously lightening the strain on the floor so it can be walked upon, DC 36 Stealth check (expert) to move carefully through the room for the remainder of your turn without triggering the hazard, or DC 36 Nature check (expert) twice once the trap is triggered to knock enough holes into the nearby walls to cause the spores to disperse"
attacks:
  - name: ""

  - name: "Collapse Floor"
    desc: "`pf2:r` **Trigger** A round begins with a Small or larger creature standing on the floor in area **A4**\n* * *\n\n**Effect** The floor of the entire room collapses in a thunderous crash, dropping all creatures in the room 5 feet into a soupy morass of mud, mold, and toxic fungus while a cloud of spores spews up into the air above. The room becomes greater difficult terrain. All creatures who were standing on the floor in the room fall [[Conditions/Prone|Prone]] in the mess below unless they succeed at a DC 34 Reflex check save, in which case they land on their feet. The hazard then rolls initiative."

  - name: "Routine"
    desc: "(1 action) Every round on its turn, the spores that now fill area **A4** inflict 8d6 poison damage to all creatures in the room (DC 30 Fortitude check save) as the cloud burns at exposed flesh; a creature that holds its breath gains a +4 circumstance bonus to this saving throw."
  - name: "Reset"
    desc: "One minute after nothing moves in the room, the spores settle down. The floor remains obvious and won't collapse further, but any creature that moves through the mold causes the spores to plume up again, re-triggering the trap."
```

```encounter-table
name: Weakened Floor
creatures:
  - 1: Weakened Floor
```

