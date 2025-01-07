---
title: Locking Alarm
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder Kingmaker
aliases: "Actor.PUuWuVKqvSwTkMVE" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Locking Alarm"
level: "Hazard 10"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder Kingmaker_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +24, __Ref__ +16, "
hp: 70
health:
  - name: ""
  - name: "HP"
    desc: "70; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Any attempt to open the door without first tracing the symbol of Yhidothrus (an hourglass) on the door's face with a fingertip causes a glowing green ward to seal the door shut and raise an alarm."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Thievery check (expert) to bypass the magical triggers on the door, or [[Spells/Dispel Magic|Dispel Magic]] (5th level, counteract DC 29) to counteract the alarm."
attacks:
  - name: ""

  - name: "Lock and Shriek"
    desc: "`pf2:r` (occult) **Trigger** A creature attempts to open or affect the door\n\n**Effect** The religious symbol of Yhidothrus glows green on the door, sealing it shut while simultaneously shrieking like a tormented soul. This howl is audible in areas **D1-D4** and is loud enough in area **D2** to rouse the bodaks.\n\nWhile the door remains locked, a DC 32 Athletics check check can Force it Open, or a DC 32 Thievery check check can Pick the Lock. The lock can also be removed with [[Spells/Dispel Magic|Dispel Magic]] (5th level, counteract DC 29).\n\nOnce triggered, the alarm continues to shriek and the door remains locked until the hazard is disabled or the door is destroyed or opened. Tracing Yhidothrus's hourglass-shaped religious symbol on either side of the door with a fingertip disables the alarm and the locking ward."


  - name: "Reset"
    desc: "The _locking alarm_ resets after 1 minute."
```

```encounter-table
name: Locking Alarm
creatures:
  - 1: Locking Alarm
```

