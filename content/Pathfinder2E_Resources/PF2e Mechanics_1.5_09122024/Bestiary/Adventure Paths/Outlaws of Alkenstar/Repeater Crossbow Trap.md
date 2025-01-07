---
title: Repeater Crossbow Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #178: Punks in a Powder Keg
aliases: "Actor.pZh7r8gIa6sf8v93" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Repeater Crossbow Trap"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 13
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +15, __Ref__ +9, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50; __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A pressure plate in the hallway floor releases a latch, causing a ceiling panel to drop down. A _+1 striking heavy crossbow_ contained in a steel box sprays bolts at any creatures in the hallway."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Thievery check (Expert) or DC 20 Crafting check (Trained) to disengage the reloading mechanism; the trap can also be disabled by the switch in area **F2**"
attacks:
  - name: ""

  - name: "Auto-Bolter"
    desc: "`pf2:r` **Trigger** An object or creature weighing at least 25 pounds steps on the pressure plate at the south end of the hallway\n* * *\n\n**Effect** A _+1 striking heavy crossbow_ encased in a steel box drops from the ceiling and fires. The repeater crossbow trap Strikes a random creature in the hallway. The trap then rolls initiative."
  - name: "Melee"
    desc: "Heavy Crossbow +16 (agile, range 120 feet, reload 2) "

  - name: "Routine"
    desc: "(3 actions) The repeater crossbow trap reloads (2 actions) then Strikes a random creature in the hallway."
  - name: "Reset"
    desc: "The trap runs out of ammo after it fires 5 bolts; it must be manually reloaded."
```

```encounter-table
name: Repeater Crossbow Trap
creatures:
  - 1: Repeater Crossbow Trap
```

