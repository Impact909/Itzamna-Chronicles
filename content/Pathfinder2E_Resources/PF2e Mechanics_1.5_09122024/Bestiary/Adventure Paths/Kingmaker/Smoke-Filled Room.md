---
title: Smoke-Filled Room
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.rD0woMIgIih93EXI" 
level: 2
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Smoke-Filled Room"
level: "Hazard 2"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: -10
sourcebook: "_Pathfinder Kingmaker_"
perception:
  - name: ""
  - name: "Stealth DC -10" 
    desc: "(noticing the smoke is automatic)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Thick smoke fills this room, making it difficult to see and breathe."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "While a spell like [[Spells/Gust of Wind|Gust of Wind]] can temporarily clear a path through the smoke, the hazard returns at the start of the next round as long as the fires in area A17 continue to burn; DC 18 Survival check to know how best to cover your nose and mouth with a wet cloth to help alleviate the choking effects of the smoke."
attacks:
  - name: ""

  - name: "Choke"
    desc: "`pf2:0` **Trigger** A creature that isn't holding their breath walks into the hallway or starts their turn in the hallway\n\n**Effect** The triggering creature must attempt a DC 18 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected by the smoke.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]] by the smoke.\n\n**Failure** The creature is sickened 1 and takes 1d6 nonlethal damage from choking on the smoke. A creature that falls [[Conditions/Unconscious|Unconscious]] from the nonlethal damage begins to suffocate in 1d4+1 rounds if not dragged to safety.\n\n**Critical Failure** As failure, but [[Conditions/Sickened|Sickened 2]] and 1d6 persistent nonlethal damage."

  - name: "Burning Room"
    desc: "passive The flames and heat deal 1d6 fire damage (DC 16 Reflex check save) to creatures who end their turns in these burning chambers as long as the fires continue.\n\nBreaking the room's glass window before the fire is extinguished causes the fire within to flare up and deal 2d6 fire damage at the end of that round (rather than the standard 1d6), but once at least three of the burning rooms have their windows ventilated, the smoke in these rooms and in area A16 lessens, and the DC of the Fortitude save to resist its Choke effect is reduced to 11."


  - name: "Reset"
    desc: "The smoke continues to affect anyone who enters area A16 until the fires in area A17 are extinguished."
```

```encounter-table
name: Smoke-Filled Room
creatures:
  - 1: Smoke-Filled Room
```

