---
title: Rogue Sphere
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #191: The Destiny War
aliases: "Actor.TtOJlbofZ9jLUZyG" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Rogue Sphere"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[magical]]
modifier: 40
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 34
armorclass:
  - name: AC
    desc: "34; "
hp: 96
health:
  - name: ""
  - name: "HP"
    desc: "96; __Hardness__ 25; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ force 15"
perception:
  - name: ""
  - name: "Stealth DC 40" 
    desc: "(master; +35 in bright light)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A roving sphere of distorted magic shimmers and floats through the air."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 38 Arcana check, DC 38 Nature check, DC 38 Occultism check, or DC 38 Religion check (master) to cause the magic of the sphere to dissipate harmlessly, or DC 40 Thievery check to cause the sphere to burst and implode safely, or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 34)"
attacks:
  - name: ""

  - name: "Magic Drift"
    desc: "`pf2:r` **Trigger** A creature within 60 feet casts a spell or uses magical effect, or a creature within 60 feet is the target of an active spell that's 5th level or higher, carries a magic item of 10th level or higher, or is the target of an ongoing magical effect created by a creature who's 10th level or higher\n* * *\n\n**Effect** The sphere flies 30 feet toward the triggering creature. If the sphere would enter a creature's space, it stops moving in that creature's space, then attempts to counter the triggering magic effect (or alternately, the strongest magic effect on the creature), with a counteract modifier of +28. A counteracted magic item becomes a mundane item of its type for 10 minutes. If the target is a creature, or is a creature who's carrying the targeted item, the creature takes 10d6 force damage from this effect (DC 36 Fortitude check save). The rogue sphere then rolls initiative."

  - name: "Routine"
    desc: "(2 actions) The sphere uses its first action to fly 30 feet toward the closest creature currently under the effects of a spell, or it uses both actions to fly 60 feet toward the closest creature if none are within 30 feet. The rogue sphere attempts to enter the target's space. If a rogue sphere shares a creature's space, it uses an action to Magic Drift the target. If the target has no magical effects or carries no magic items, the result of its Fortitude save to resist the force damage caused by Magic Drift is increased by one degree of success."
  - name: "Reset"
    desc: "The sphere ceases moving when no creature remains to trigger Magic Drift. It then dissipates after an hour spent with no targets within 60 feet"
```

```encounter-table
name: Rogue Sphere
creatures:
  - 1: Rogue Sphere
```

