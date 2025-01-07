---
title: Battle Illusion
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - haunt
  - occult
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #208: Hoof, Cinder, and Storm
aliases: "Actor.iD9CQ5uY3x9jsSYz" 
level: 9
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Battle Illusion"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[haunt]]
trait_03: [[occult]]
modifier: 24
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
perception:
  - name: ""
  - name: "Stealth DC 24" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The scene of the arid Cinderlands melts away as the water of the river refills and green grass spreads across the land. The sounds of battle can be heard everywhere and all allies have vanished, murderous orcs from the One Eye Hold taking their place."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Occultism check or DC 30 Religion check (expert) twice to weaken the haunt or [[Spells/Dispel Magic|Dispel Magic]] (4th rank; counteract DC 27) to counteract the illusions"
attacks:
  - name: ""

  - name: "Cries of War"
    desc: "`pf2:r` (illusion, incapacitation, mental, occult, visual) **Trigger** Two or more creatures enter the haunt's area\n* * *\n\n**Effect** Each creature sees the forms of nearby allies shift and fade, replaced with hostile One Eye orcs. Each creature in the area must attempt a DC 30 Will check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature sees through the illusions and is temporarily immune to the haunt's routine for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature believes the illusions are true; if they become [[Conditions/Confused|Confused]] by the haunt's routine, they can't attempt flat checks to end the confused condition when they take damage.\n\n**Critical Failure** As failure and the creature is filled with feelings of abandonment and betrayal. When the creature rolls against the haunt's routine, they must roll twice and take the worse result. This is a misfortune effect."

  - name: "Routine"
    desc: "(1 action; illusion, incapacitation, mental, occult) The haunt continues the illusion, making victims feel as though they've been abandoned and are surrounded by attackers on all sides. Each creature in the haunt's area must make a DC 28 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The creature is hostile toward the supposed One Eye orcs and must spend all actions moving toward and attacking One Eye orcs. This hostility lasts for 1 minute, until the haunt is disabled, or until they fall [[Conditions/Unconscious|Unconscious]]. They cannot voluntarily stop attacking those they perceive as enemies."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all creatures leave the Shadefields but resets immediately. The battle illusion resets 1 day after being disabled if the ancestor storm isn't put to rest."
```

```encounter-table
name: Battle Illusion
creatures:
  - 1: Battle Illusion
```

