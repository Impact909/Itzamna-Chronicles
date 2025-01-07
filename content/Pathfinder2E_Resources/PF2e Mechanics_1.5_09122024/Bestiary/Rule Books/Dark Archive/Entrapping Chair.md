---
title: Entrapping Chair
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder Dark Archive
aliases: "Actor.1OXsTTCAARptWZIx" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Entrapping Chair"
level: "Hazard 5"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 16
sourcebook: "_Pathfinder Dark Archive_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +9, "
hp: 54
health:
  - name: ""
  - name: "HP"
    desc: "54; __Hardness__ 14; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 26" 
    desc: "(0 to notice the chair)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A chair on concealed tracks surges forward, knocking a creature into the chair's seat and trapping them in place with clamping armrests."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Thievery check (expert) to disrupt the tracks"
attacks:
  - name: ""

  - name: "Take a Seat!"
    desc: "`pf2:r` **Trigger** A creature steps on the track\n* * *\n\n**Effect** The chair rockets forward along the track and slams into the triggering creature, dealing 3d8 + 15 bludgeoning damage. A creature who succeeds at a DC 22 Reflex check save takes no damage and moves out of the chair's path into a random adjacent square not containing the track. A creature who fails this saving throw is knocked into the chair's seat and immediately captured by the armrests, becoming [[Conditions/Grabbed|Grabbed]] ([[Conditions/Restrained|Restrained]] on a critical failure; Escape DC 26)."


  - name: "Reset"
    desc: "The trap resets automatically over 2 rounds if the chair is unoccupied."
```

```encounter-table
name: Entrapping Chair
creatures:
  - 1: Entrapping Chair
```

