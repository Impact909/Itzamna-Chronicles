---
title: Shuffling Scythe Blades
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #164: Hands of the Devil
aliases: "Actor.kjE5Xha44X5sKmXt" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Shuffling Scythe Blades"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 18
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +13, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 16; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Six long blades, hidden in grooves in the walls and floor, zigzag through different parts of this hallway when any pressure plate in the hallway intersection is depressed; there are so many plates it's impossible to avoid them when moving through the room. The blades retreat into the floor and move through the hidden grooves before swinging out from the wall again in a different location."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 26 Thievery check (expert) to disable each blade, or utter the magical passphrase (which only Chafkhem knows) to deactivate the trap for 10 minutes"
attacks:
  - name: ""

  - name: "Dicing Scythes"
    desc: "`pf2:r` **Trigger** A creature steps in the 15-footby-25-foot area where the branching hallways connect\n* * *\n\n**Effect** The trap uses Scythe Shuffle; each blade makes a scythe Strike against each creature in its region, then it uses Scythe Shuffle again. The trap then rolls for initiative."

  - name: "Scythe Shuffle"
    desc: "action The blades travel erratically throughout the hallway's branches, out of sight under the floors or behind the walls. For each blade, roll 1d4 to determine the region in which it next makes scythe Strikes. A creature can [[Actions/Seek|Seek]] (DC 22 Perception check) to learn clues about blades in the region they're currently occupying. On a success, the creature knows how many blades are currently in its region.\n\n1. Main intersection (the 15-foot-by-25-foot area where the hallways connect, as marked on area **B20**)\n\n2. North branch (from the main intersection to the secret door to area **B14**)\n\n3. Central hall (from the main intersection to the secret door to area **B24**)\n\n4. South branch (from the main intersection to the wall shared with area **B25**)"
  - name: "Melee"
    desc: "Scythe +20 (deadly d12) No MAP applies to strikes made by scythe attacks"

  - name: "No MAP"
    desc: "passive The Scythe Strikes do not apply a MAP."

  - name: "Routine"
    desc: "(7 actions) The trap spends 1 action for each of its blades; a blade makes a scythe Strike against each creature in its region. With its final action, the trap uses Scythe Shuffle. Reduce the number of actions the trap can take by 1 for each destroyed blade."
  - name: "Reset"
    desc: "The trap resets when no creatures remain in area **B20**. Damaged or destroyed blades aren't repaired when the trap resets."
```

```encounter-table
name: Shuffling Scythe Blades
creatures:
  - 1: Shuffling Scythe Blades
```

