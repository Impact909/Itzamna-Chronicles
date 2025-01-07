---
title: Forest Fire
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - fire
  - pf2eHazard
  - complex
source: Pathfinder #176: Lost Mammoth Valley
aliases: "Actor.q202XIMfpUnKNblZ" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Forest Fire"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[fire]]
modifier: -10
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC -10" 
    desc: " -10"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 10‑foot‑by‑10‑foot bonfire spreads to the surrounding forest on each of its turns."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "A successful DC 22 Athletics check, DC 22 Nature check, or DC 22 Survival check check from an adjacent square is sufficient to smother one 5‑foot‑square of fire; each attempt is an Interact action. Dousing the flames automatically extinguishes one or more sections of fire, with no check. Water typically clears a 5‑foot square if the amount is small (such as from a spell like create water or hydraulic push). Larger amounts of water, such as a full bucket, typically douse a 10‑foot‑by‑10‑foot area (or 4 squares in some other shape). Throwing a bucket of water on flames requires an Interact action. A waterskin doesn't contain enough water to put out even 1 square of fire. Cold can also put out fire, but only if the cold can affect an area; cold is less effective than water, so a frost vial puts out only 1 square of fire, and a ray of frost is ineffective."
attacks:
  - name: ""

  - name: "Stoke Flames"
    desc: "`pf2:r` **Trigger** A brimorak urges the fire to spread out of control\n* * *\n\n**Effect** The bonfire becomes a forest fire and rolls initiative."

  - name: "Routine"
    desc: "On its turn, the fire spreads into a number of additional squares equal to half the number of squares the fire currently occupies (minimum 1 square). You determine the squares the fire spreads into. Any creature that ends its turn next to the flames takes 2d8+5 fire damage, or 4d8+10 fire damage if it ended its turn within the flames (DC 25 Reflex check in either case). A creature can take damage from the forest fire only once per round."

```

```encounter-table
name: Forest Fire
creatures:
  - 1: Forest Fire
```

