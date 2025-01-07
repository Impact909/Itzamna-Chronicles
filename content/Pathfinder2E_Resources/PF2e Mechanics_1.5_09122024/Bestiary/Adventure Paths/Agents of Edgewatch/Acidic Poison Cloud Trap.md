---
title: Acidic Poison Cloud Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - alchemical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #159: All or Nothing
aliases: "Actor.pQXfSDtof52u3mR6" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Acidic Poison Cloud Trap"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[alchemical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 30
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +28, __Ref__ +20, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40, to destroy a nozzle; &lt;strong&gt;Tank Hardness&lt;/strong&gt; 20; &lt;strong&gt;TankHP&lt;/strong&gt; 100 (BT 50) to damage the tank enough to stop it from spewing gas; __Hardness__ 15; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 30" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Five nozzles hidden across the apartment's ceiling spew thick clouds of acidic poison from a reinforced tank behind the wall."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 35 Thievery check (expert) to block one of the nozzles or DC 40 Thievery check (master) to shut off the tank. The trap deactivates after 5 rounds, once the tank is empty."
attacks:
  - name: ""

  - name: "Spew Cloud"
    desc: "`pf2:r` **Trigger** Twelve seconds have passed since the door to the apartment was opened\n* * *\n\n**Effect** The trap rolls initiative."

  - name: "Routine"
    desc: "(1 action) When it's triggered, the trap has five active nozzles, but at the end of its turn each round, one random nozzle deactivates. On the trap's turn, the active nozzles emit a cloud of acidic poison gas that expands to fill the apartment. The cloud deals 1d6 acid damage and 1d6 poison damage per active nozzle to each creature and object in the room (DC 33 Fortitude check save). Unattended objects automatically fail saves to avoid the damage."

```

```encounter-table
name: Acidic Poison Cloud Trap
creatures:
  - 1: Acidic Poison Cloud Trap
```

