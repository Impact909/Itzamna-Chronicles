---
title: Tar Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #177: Burning Tundra
aliases: "Actor.mBUpsd8Ogxe8MJM2" 
level: 9
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Tar Pit"
level: "Hazard 9"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 20
sourcebook: "_Pathfinder #177: Burning Tundra_"
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
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 15-foot-wide patch of tar covered with dirt and leaves attempts to capture creatures that step onto it."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Survival check (expert) to disturb the surface and reveal the tar pit"
attacks:
  - name: ""

  - name: "Capture"
    desc: "`pf2:r` **Trigger** A Huge or smaller creature walks onto the tar pit\n* * *\n\n**Effect** The triggering creature sinks into the tar pit up to its waist. The tar pit rolls initiative if it hasn't already."

  - name: "Routine"
    desc: "(1 action) On its initiative, the tar pit pulls down each creature within it, thick tar adhering to the creature's body. A creature that was submerged up to its waist becomes submerged up to its neck, and a creature that was submerged up to its neck is pulled under and must hold its breath to avoid suffocation. A creature in the tar pit can attempt a DC 33 Athletics check check to [[Actions/Climb|Climb]] to either raise itself by one step (if it's submerged to its neck or full submerged) or to move 5 feet if it's submerged only up to its waist. On a critical failure, the creature is pulled down one step. Other creatures can Aid the creature, typically by using a rope or similar aid or by attempting to pull the creature out with their own DC 33 Athletics check check, with the same results as if the creature attempted the check. In addition to the usual results, a character adjacent to the tar pit who critically fails while Aiding moves into the tar pit. A creature that Climbs out of the tar pit escapes the hazard and lands [[Conditions/Prone|Prone]] in an adjacent space."
  - name: "Reset"
    desc: "Though the hazard still captures anyone who touches it, the surface doesn't become hidden again until it settles, which takes 24 hours."
```

```encounter-table
name: Tar Pit
creatures:
  - 1: Tar Pit
```

