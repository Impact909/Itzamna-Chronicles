---
title: Death's Slumber Ward
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #175: Broken Tusk Moon
aliases: "Actor.s5ocmQRiWEDXGhmJ" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #175: Broken Tusk Moon"
name: "Death's Slumber Ward"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 16
sourcebook: "_Pathfinder #175: Broken Tusk Moon_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 16" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A whirlwind of four ephemeral, magical threads dispels the undead and shrouds the living in an endless slumber."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 23 Religion check (expert) or DC 21 Performance check (trained) to dissipate one of the four threads. Characters who failed or critically failed a Performance check to participate in Grandfather Eiwa's funeral in Chapter 1 have been able to reflect on the experience; these characters gain a +2 circumstance bonus to their Performance checks to disable this trap.\n\nThe trap is destroyed when all four threads are dissipated."
attacks:
  - name: ""

  - name: "Breath of Pharasma"
    desc: "`pf2:r` (divine) **Trigger** A living or undead creature opens the trunk\n* * *\n\n**Effect** The ephemeral winds rise, sapping energy. All living and undead creatures within 60 feet must succeed at a DC 22 Will check save or become [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The trap then rolls initiative."

  - name: "Routine"
    desc: "(4 actions) Each thread of energy passes through a random living or undead creature within 60 feet, dealing 4d6 damage (DC 22 Will check) to the creature. A thread deals 4d6 void damage to living creatures and 4d6 vitality damage to undead creatures. Each thread passes through a different random creature, if possible. Each dissipated thread reduces the trap's number of actions by 1."
  - name: "Reset"
    desc: "The haunt deactivates 1 minute after no living or undead creatures are within 100 feet, then resets."
```

```encounter-table
name: Death's Slumber Ward
creatures:
  - 1: Death's Slumber Ward
```

