---
title: Abyss-warped Trees
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #176: Lost Mammoth Valley
aliases: "Actor.o3bqZMvKNlcmEW5w" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Abyss-warped Trees"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 2
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +14, __Ref__ +14, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40, per tree; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 5"
perception:
  - name: ""
  - name: "Stealth DC 2" 
    desc: "(trained) to determine the trees can move"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A forest of fiendish trees swing their branches and shift their roots to bludgeon and trip creatures in the tainted grove (area **A21**)."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Survival check (trained) to find a location the trees can't reach or DC 24 Religion check to recite a prayer that temporarily casts out the fiendish energy inside a single tree in the grove, disabling it for 1 minute. A disabled or destroyed tree creates a 5‑foot‑square area in the grove that's safe from this hazard."
attacks:
  - name: ""

  - name: "Shift Roots"
    desc: "`pf2:r` **Trigger** A creature ends its movement in the grove\n* * *\n\n**Effect** The trees throughout the tainted grove shift their roots wildly, making the area difficult terrain, then the Abyss-warped trees roll initiative."

  - name: "Tighten Grip"
    desc: "`pf2:0` **Trigger** The Abyss-warped trees critically hit a creature with a branch Strike\n* * *\n\n**Effect** The Abyss-warped trees loop their branches around the triggering creature, [[Conditions/Grabbed|Grabbing]] it ([[Actions/Escape|Escape]] DC 21)."
  - name: "Melee"
    desc: "Branch +14 () "

  - name: "Routine"
    desc: "(4 actions) The Abyss‑warped trees use their first action each round to lash their roots; each creature in the tainted grove must succeed at a DC 21 Reflex check save or fall [[Conditions/Prone|Prone]]. The Abyss‑warped trees use their second, third, and fourth actions to make branch Strikes against up to three different creatures in the tainted grove."
  - name: "Reset"
    desc: "The Abyss-warped trees cease moving 1 minute after no living creatures are in the tainted grove. They reset immediately. A disabled tree reanimates after 1 minute. A destroyed tree regrows after 1 month."
```

```encounter-table
name: Abyss-warped Trees
creatures:
  - 1: Abyss-warped Trees
```

