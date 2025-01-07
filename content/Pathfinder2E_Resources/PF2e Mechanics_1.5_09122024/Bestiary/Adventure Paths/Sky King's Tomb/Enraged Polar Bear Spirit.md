---
title: Enraged Polar Bear Spirit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #195: Heavy is the Crown
aliases: "Actor.xlFbA19TMgZCLKoH" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #195: Heavy is the Crown"
name: "Enraged Polar Bear Spirit"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 13
sourcebook: "_Pathfinder #195: Heavy is the Crown_"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: " +13"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The ghostly spirit of a polar bear stands on its hind legs and roars."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Nature check (expert) to calm the spirit, DC 30 Intimidate check (master) to cow the spirit, or DC 30 Religion check (expert) to contain the spiritual corruption (each successful check reduces its number of actions by 1)"
attacks:
  - name: ""

  - name: "Feral Roar"
    desc: "action (auditory, fear, mental) **Trigger** A creature approaches within 10 feet of the polar bear spirit\n* * *\n\n**Effect** The polar bear spirit roars. Each creature in the room must attempt a DC 28 Will check save. The enraged polar bear spirit rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes 6d6 sonic damage and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature takes 12d6 sonic damage and is [[Conditions/Frightened|Frightened 3]]."
  - name: "Melee"
    desc: "Spiritual Claws +21 (agile, magical) "

  - name: "Routine"
    desc: "(3 actions) The bear moves around the room at an alarming speed, seemingly teleporting, and Strikes a random creature with its spiritual claws."
  - name: "Reset"
    desc: "The bear spirit calms after no creatures are in the room for 1 minute but is ready to lash out again after 10 minutes."
```

```encounter-table
name: Enraged Polar Bear Spirit
creatures:
  - 1: Enraged Polar Bear Spirit
```

