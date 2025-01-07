---
title: Clone Mirrors
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.mAQNiyTsR9cIbv3S" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Clone Mirrors"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 11
sourcebook: "_Pathfinder Dark Archive_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +17, __Ref__ +11, "
hp: 54
health:
  - name: ""
  - name: "HP"
    desc: "54, per mirror; __Hardness__ 13; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 11" 
    desc: " +11"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Two opposing mirrors spawn illusory duplicates of creatures in the hall in an unending tide."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (expert) to reposition each mirror, or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 25) to counteract each mirror"
attacks:
  - name: ""

  - name: "Spawn Reflection"
    desc: "`pf2:r` (illusion) **Trigger** A creature is reflected in the mirror\n* * *\n\n**Effect** The mirror creates a [[Dark Archive/Reflection|Reflection]] of the triggering creature, which Steps out of the mirror and into the hall. The trap then rolls initiative."

  - name: "Routine"
    desc: "(2 actions) This trap loses 1 action for each mirror disabled. Each mirror uses 1 action to Spawn a Reflection of a creature reflected in the mirror. The hazard can have a maximum of four reflections spawned at once."
  - name: "Reset"
    desc: "1 day"
```

```encounter-table
name: Clone Mirrors
creatures:
  - 1: Clone Mirrors
```

