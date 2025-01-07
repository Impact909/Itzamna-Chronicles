---
title: Telekinetic Swarm Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder Core Rulebook
aliases: "Actor.9DlrOJy0UzAvBjr8" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Core Rulebook"
name: "Telekinetic Swarm Trap"
level: "Hazard 12"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
modifier: 24
sourcebook: "_Pathfinder Core Rulebook_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +19, "
hp: 88
health:
  - name: ""
  - name: "HP"
    desc: "88, per telekinetic cloud; __Hardness__ 22; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 24" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three innocuous decorations instilled with telekinetic magic pull objects and pieces of the room itself into spinning clouds of debris that attack all creatures in the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Thievery check (expert) to take apart a telekinetic cloud, DC 32 Thievery check (master) to disable each telekinetic decoration, or [[Spells/Dispel Magic|Dispel Magic]] (6th level; counteract DC 30) to counteract each telekinetic decoration"
attacks:
  - name: ""

  - name: "Agitate"
    desc: "`pf2:r` (arcane) **Trigger** A creature stays in the room for at least 6 seconds.\n* * *\n\n**Effect** Each telekinetic decoration constructs a cloud of objects in the room (three clouds total) and the trap rolls initiative. The creatures in the room when the trap is triggered become the trap's targets, regardless of whether they leave the room or other creatures later enter the room. Each decoration targets a different creature if possible. A target creature that moves at least 1 mile from the trap ceases being a target, at which point the decoration designates a new target."
  - name: "Melee"
    desc: "Objects +24 () "

  - name: "Routine"
    desc: "(9 actions) Each decoration uses 3 of the trap's actions each turn, and the trap loses 3 actions each turn for every decoration that is disabled. A decoration uses its first action to move its cloud of objects up to 200 feet, its second action to make the objects Strike, and its third action to add more objects to the cloud, increasing its damage by 1d12 (to a maximum of 4d12+10). If a decoration's cloud is already at maximum damage, it does nothing with its third action.\n\nIf a decoration's cloud has been destroyed, the decoration instead spends its first action to create a new cloud of objects inside the room (using the starting damage value) and then its second and third actions to have the cloud move and attack."
  - name: "Reset"
    desc: "The trap deactivates and resets 10 minutes after it has no target creatures (because the creatures either moved too far away or died)."
```

```encounter-table
name: Telekinetic Swarm Trap
creatures:
  - 1: Telekinetic Swarm Trap
```

