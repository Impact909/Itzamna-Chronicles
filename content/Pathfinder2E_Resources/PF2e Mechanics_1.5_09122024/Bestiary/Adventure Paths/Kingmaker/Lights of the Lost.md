---
title: Lights of the Lost
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Kingmaker
aliases: "Actor.s5qq8nZrM2s48UkO" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Lights of the Lost"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 32
sourcebook: "_Pathfinder Kingmaker_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +23, __Ref__ +26, __Will__ +29"
hp: 106
health:
  - name: ""
  - name: "HP"
    desc: "106; __Hardness__ 25; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 15"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The murdered spirits of the slain priests manifest as churning, glowing spheres of floating, blood- red wine that drift and slither through the air. Within each can be glimpsed a silently screaming face."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Diplomacy check check to promise the restless spirits that justice will be served and the cause of their pain will be punished, or DC 36 Religion check to invoke Cayden Cailean to calm the haunt."
attacks:
  - name: ""

  - name: "Waves of Fear"
    desc: "`pf2:r` (divine, emotion, fear, mental) **Trigger** A creature opens any of the doors into a priest's cell\n* * *\n\n**Effect** Waves of fear wash through area **A12** as all creatures in the room realize that, one by one, their loved ones are being murdered and that they will be the last to be slain. Every creature in area **A12** must attempt a DC 37 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature becomes [[Conditions/Frightened|Frightened 2]] and [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** The creature becomes [[Conditions/Frightened|Frightened 3]] and [[Conditions/Stunned|Stunned 3]]."

  - name: "Routine"
    desc: "(3 actions) Up to four different creatures in area **A12** are each targeted by one of the floating, churning spheres of wine drifting through the air; it hurtles toward them and douses them with wine that turns to life- draining blood as it strikes unerringly. The haunt cannot target the same creature more than once each round. After the haunt is reduced to its broken threshold of 53 HP, it can target no more than two different creatures. A creature targeted by the lights of the lost must attempt a DC 37 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d6 void damage and is [[Conditions/Sickened|Sickened 1]] from drunkenness.\n\n**Failure** The creature takes 8d6 void damage and is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The takes 16d6 void damage, is [[Conditions/Sickened|Sickened 3]], and becomes [[Conditions/Doomed|Doomed 1]]. As long as the creature is doomed from this trap, they cannot reduce their sickened condition below 1, and they take a -1 circumstance penalty on all further saving throws made against fear effects as lingering traces of the terror the priests felt loom in their memories."
  - name: "Reset"
    desc: "1 hour"
```

```encounter-table
name: Lights of the Lost
creatures:
  - 1: Lights of the Lost
```

