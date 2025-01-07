---
title: Toxic Crystals
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #200: Seven Dooms for Sandpoint
aliases: "Actor.bjILS6mfhdXlFU5n" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #200: Seven Dooms for Sandpoint"
name: "Toxic Crystals"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 13
sourcebook: "_Pathfinder #200: Seven Dooms for Sandpoint_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +20, __Ref__ +12, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision,  fire; __Weaknesses__ sonic 10"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The green crystals begin to pulse more brightly with light in the presence of living creatures. These fluctuations in illumination from different crystals eerily match the pace of the breathing and rhythm of the heartbeats of those in the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 30 Thievery check (expert) to create a chain reaction among the crystals by striking them in precise spots that cause them to shatter and harmlessly discharge their energy, or DC 27 Performance check (expert) to use a musical instrument or singing to resonate the crystals and discharge their toxic energy harmlessly"
attacks:
  - name: ""

  - name: "Nauseating Pulse"
    desc: "`pf2:r` (poison) **Trigger** A living creature comes within 20 feet of the green crystals\n* * *\n\n**Effect** The crystals pulse with nauseating light. All creatures in area **E14** or within the first 10 feet of either passage leading out of this area must succeed at a DC 25 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (or [[Conditions/Sickened|Sickened 3]] on a critical failure)."

  - name: "Routine"
    desc: "(1 action) (light, poison) Each round on their action, the toxic crystals emit a shrill humming sound and flash brightly with green light. All creatures in area **E14** or within the first 10 feet of either passage leading out of this area must attempt a DC 25 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d8 poison damage.\n\n**Failure** The creature takes 4d8 poison damage and is [[Conditions/Dazzled|Dazzled]] for 1 minute.\n\n**Critical Failure** The creature takes 4d8 poison damage, becomes [[Conditions/Enfeebled|Enfeebled 1]], and is [[Conditions/Blinded|Blinded]] for 1 minute."
  - name: "Reset"
    desc: "The toxic crystals become dormant once no living creatures are in range, but can activate again as soon as another living creature comes in range."
```

```encounter-table
name: Toxic Crystals
creatures:
  - 1: Toxic Crystals
```

