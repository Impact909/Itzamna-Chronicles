---
title: Hall of Mirrors
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #182: Graveclaw
aliases: "Actor.KEVH7oBi3nEpZULP" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Hall of Mirrors"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 16
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +13, __Ref__ +19, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 16" 
    desc: " +16"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Among the many mirrored reflections lurk three trapped souls. By attacking reflections, these spirits cause wounds to appear on the bodies of those reflected in the mirror. If a trapped soul kills its victim, the soul escapes the mirror, replaced by its victim's soul."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 24 Occultism check (expert) to realign a mirror so a trapped soul can't hurt the reflections, DC 28 Religion check (expert) to banish a trapped soul, or DC 28 Thievery check (expert) to cover a mirror quickly enough to keep the trapped soul inside it; each successful attempt to disable the haunt reduces its number of actions by 1"
attacks:
  - name: ""

  - name: "Ghostly Images"
    desc: "`pf2:r` (fear, mental, occult) **Trigger** Two or more creatures enter the room\n* * *\n\n**Effect** Three trapped souls appear in mirrors throughout the room, menacing the reflections of the triggering creatures. The triggering creatures must each succeed at a DC 28 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 3]] on a critical failure). The haunt then rolls initiative."

  - name: "Soul Shred"
    desc: "passive A creature damaged by the haunt's reflective ripple Strike is [[Conditions/Enfeebled|Enfeebled 1]] until 1 minute after it leaves the room. This enfeebled condition is cumulative, up to enfeebled 4. If the creature dies from reflective rip, its soul is contained within the mirror until the mirror is broken and a [[Bestiary 2/Specter|Specter]] emerges."
  - name: "Melee"
    desc: "Reflective Rip +20 () "

  - name: "Routine"
    desc: "(3 actions) Each trapped soul makes a reflective rip Strike against the reflection of a creature in the room; each trapped soul must attack a different target."

```

```encounter-table
name: Hall of Mirrors
creatures:
  - 1: Hall of Mirrors
```

