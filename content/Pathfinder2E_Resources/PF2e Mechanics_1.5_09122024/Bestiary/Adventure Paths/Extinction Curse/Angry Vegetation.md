---
title: Angry Vegetation
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard
  - complex
source: Pathfinder #156: The Apocalypse Prophet
aliases: "Actor.2c5PLfLrWQq9ehlE" 
level: 20
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Angry Vegetation"
level: "Hazard 20"

trait_06: "Complex"
trait_01: [[environmental]]
modifier: 32
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +33, __Ref__ +30, __Will__ +30"
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120, per flower; __Immunities__  object immunities,  mental; __Weaknesses__ fire 20"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "DC 42 Perception check (master) to notice massive buds beneath the other foliage before they open"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Five large flowers in the weed-choked field unfurl, each dusting pollen onto vines that animate into [[Bestiary 1/Wemmuth|Wemmuths]]."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 48 Nature check (master) or DC 48 Performance check (legendary) to calm a flower, closing it"
attacks:
  - name: ""

  - name: "Bloom"
    desc: "`pf2:r` **Trigger** A non-plant creature enters the garden\n* * *\n\n**Effect** The blooms open, spawning a single [[Bestiary 1/Wemmuth|Wemmuth]] that acts on the hazard's initiative, and the hazard rolls for initiative."

  - name: "Routine"
    desc: "`pf2:2` If there are fewer wemmuths than open flowers, the flowers create more wemmuths (so there as many wemmuths as open flowers) as their first action.\n\nFor their second action, the flowers produce a mind-addling pollen. Each non-plant creature within 30 feet of a flower must succeed at a DC 41 Fortitude check save or become [[Conditions/Slowed|Slowed 1]] for 1 round (or [[Conditions/Confused|Confused]] for 1 round, on a critical failure). The pollen is an emotion, mental, and olfactory effect."
  - name: "Reset"
    desc: "Wemmuths collapse into ordinary vines and the trap resets if the area is left alone for 1 minute."
```

```encounter-table
name: Angry Vegetation
creatures:
  - 1: Angry Vegetation
```

