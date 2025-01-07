---
title: Confounding Betrayal
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.sFHviAwaJR6FztM4" 
level: 8
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Confounding Betrayal"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 21
sourcebook: "_Pathfinder GM Core_"
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
  - name: "Stealth DC 21" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Allies appear to shed their disguises and reveal themselves to be malevolent monsters."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Deception check (expert) twice to confound the haunt with your own deceptions, or DC 28 Occultism check (trained) twice to create a ward against the haunt's mental influence"
attacks:
  - name: ""

  - name: "Unmask"
    desc: "`pf2:r` (illusion, occult) **Trigger** Two or more creatures enter the haunt's area\n* * *\n\n**Effect** Each creature sees the forms of nearby creatures shift and change, appearing to transform into fiendish or aberrant beings with a thirst for blood. Each creature in the area must attempt a DC 30 Will check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature sees through the illusions entirely and is temporarily immune to the haunt's routine for 1 minute.\n\n**Success** The creature is unaffected by the strange images.\n\n**Failure** The creature believes the illusions to be true; if they become [[Conditions/Confused|Confused]] by the haunt's routine, they can't attempt flat checks to end the confused condition when they take damage.\n\n**Critical Failure** As failure, but the creature is left with a lingering suspicion of others and can't benefit from Aid reactions for 24 hours."

  - name: "Routine"
    desc: "(1 action; illusion, incapacitation, occult) The haunt continues to confound victims' senses and inspire them to commit violence against each other. Each creature in the haunt's area must attempt a DC 26 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and temporarily immune for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** The creature is confused for 1 minute."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after all creatures leave the area but resets immediately thereafter."
```

```encounter-table
name: Confounding Betrayal
creatures:
  - 1: Confounding Betrayal
```

