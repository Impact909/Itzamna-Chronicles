---
title: The Last Crucible
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Crown of the Kobold King
aliases: "Actor.VVMmRjOANgC0J6oj" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "The Last Crucible"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 5
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +17, __Ref__ +11, "
hp: 58
health:
  - name: ""
  - name: "HP"
    desc: "58, BT 29 to smash a 5-ft-sq hole in the wall; Spout H 13; Spout HP 20 (BT 10); __Hardness__ 15; __Immunities__  object immunities,  critical hits,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 5" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Magically hardened sheets of obsidian drop down over the room's exits while the machinery within taps into wells of magma to begin spewing lava-and monsters-into the maze."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 28 Thievery check (expert) to disable the main pressure plate at area **H4a** and deactivate the trap entirely (this causes the obsidian walls to retract up into the ceiling as well), DC 25 Thievery check (trained) to disable one of the three lava spouts, or DC 28 Athletics check (trained) to [[Actions/Force Open|Force Open]] a fallen obsidian wall"
attacks:
  - name: ""

  - name: "Drop the Wall"
    desc: "`pf2:r` **Trigger** Four or more Small or larger creatures walk onto the pressure plate at area **H4a**;\n* * *\n\n**Effect** A magically hardened sheet of obsidian drops down like a portcullis in the western and northern entrances to this room that lead to areas **H3** and **H5**, respectively. Any creatures standing in one of these squares takes 4d6 + 4 bludgeoning damage from the falling wall (DC 24 Reflex check) and then decides what side of the wall they want to be on. At the same moment, four thoqquas that have spent centuries in hibernation awaken and emerge from vents into area **H4b**. The trap then rolls initiative, as do the thoqquas."
  - name: "Melee"
    desc: "Lava Gout +17 (fire) This attack has no multiple attack penalty."

  - name: "Routine"
    desc: "(3 actions) The trap loses 1 action per disabled spout each turn. On each action, a different spout located at one of the three areas marked **H4c** spews a gout of lava at the closest non-thoqqua target in its line of sight; these spouts use magical sensors that have darkvision and a Perception DC of 25. Originally, agents of the abbot would come through here after the trap was triggered, deactivate it, and clean out the hardened blobs of lava and dead bodies that remained, but the amount of time it would take for this trap to clog tunnels with cooled lava makes tracking that slow accretion over the course of this adventure unnecessary."
  - name: "Reset"
    desc: "The Last Crucible deactivates and resets 10 minutes after it has no target creatures (because the creatures either left area **H4** or died). Any thoqquas that still live sense the magma river at area **H6** and eventually make their way north to that area to swim away."
```

```encounter-table
name: The Last Crucible
creatures:
  - 1: The Last Crucible
```

