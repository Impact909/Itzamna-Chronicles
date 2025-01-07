---
title: Rusty Floor Spikes
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Adventure: Rusthenge
aliases: "Actor.Xh5LMbnXPlYt1gPD" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Rusty Floor Spikes"
level: "Hazard 2"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 8
sourcebook: "_Pathfinder Adventure: Rusthenge_"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Pressure plates on the floor near the north door cause rusty spikes to lance up out of the floor in area **C3**."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Thievery check (trained) to disable the pressure plates."
attacks:
  - name: ""

  - name: "Spring Up"
    desc: "`pf2:r` (attack) **Trigger** A creature steps on the pressure plate\n* * *\n\n**Effect** The spikes spring up, Striking all creatures in the hallway. The floor becomes greater difficult terrain."
  - name: "Melee"
    desc: "Rusty Spike +11 () "

  - name: "Tetanus"
    desc: "passive (disease) An infection introduced through open wounds, tetanus can produce stiffness, muscle spasms strong enough to break bones, and ultimately death.\n\n**Saving Throw** DC 14 Fortitude check\n\n**Onset** 10 days\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 week)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and can't speak (1 day)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] with spasms (1 day)\n\n**Stage 4** death"


  - name: "Reset"
    desc: "Turn the resetting wheel in the eastern Inner Guard Station (area **C8b**)."
```

```encounter-table
name: Rusty Floor Spikes
creatures:
  - 1: Rusty Floor Spikes
```

