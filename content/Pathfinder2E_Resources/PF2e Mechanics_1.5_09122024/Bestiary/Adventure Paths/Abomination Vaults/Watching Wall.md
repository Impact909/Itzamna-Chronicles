---
title: Watching Wall
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #163: Ruins of Gauntlight
aliases: "Actor.iz6KoxNMLXEwRAsl" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Watching Wall"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 12
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +8, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 5"
perception:
  - name: ""
  - name: "Stealth DC 12" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An overwhelming feeling of being watched wells up in the minds of those in the room, an instant before an eerie red eye opens in the western wall."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Deception check (trained) to appear uninteresting to the watching eye (and thus be ignored by it) or DC 22 Religion check (trained) to ward against being seen by or affected by the eye."
attacks:
  - name: ""

  - name: "Someone is Watching"
    desc: "`pf2:r` (emotion, fear, mental) **Trigger** A living creature remains in area **C4** for at least 1 round\n* * *\n\n**Effect** An overwhelming wave of paranoia fills area **C4**. Each creature in the room must attempt a DC 25 Will check save, with the following results. An eerie red eye then opens in the center of the western wall, looking about the room, and the haunt rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Frightened|Frightened 1]] and feels like someone or something is watching them for as long as they remain frightened.\n\n**Failure** The creature becomes [[Conditions/Frightened|Frightened 2]] and treats no one as an ally as long as they remain frightened.\n\n**Critical Failure** The creature becomes [[Conditions/Frightened|Frightened 3]] and is [[Conditions/Confused|Confused]] as long as they remain frightened."

  - name: "Routine"
    desc: "(1 action) The eye glances about, and those it can see (whether in area **C4** or outside of it) take 4d6 mental damage (DC 21 Will check save) as fears of being watched impart ripples of pain.\n\nA creature that takes mental damage from this effect doesn't reduce their [[Conditions/Frightened|Frightened]] value at the end of their next turn."
  - name: "Reset"
    desc: "The haunt becomes inert at the end of any round in which there are no [[Conditions/Frightened|Frightened]] creatures it can see. It stays dormant for 1 hour, after which point it resets."
```

```encounter-table
name: Watching Wall
creatures:
  - 1: Watching Wall
```

