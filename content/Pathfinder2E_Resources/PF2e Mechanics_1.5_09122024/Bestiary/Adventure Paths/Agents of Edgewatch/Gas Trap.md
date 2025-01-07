---
title: Gas Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.D6OKAWVckfcEahd6" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Gas Trap"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 14
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 52
health:
  - name: ""
  - name: "HP"
    desc: "52; __Hardness__ 13; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 14" 
    desc: "(trained) to smell the poison gas or hear it hissing"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A spring slams and locks the room's door before four hidden gas vents begin pumping poison gas into the chamber."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Four DC 20 Thievery check checks to block the gas vents, or a DC 26 Thievery check check to unlock the door and escape"
attacks:
  - name: ""

  - name: "Toxic Gas"
    desc: "`pf2:r` **Trigger** A creature opens one of the drawers\n* * *\n\n**Effect** The door to the room slams shut and locks and the trap rolls initiative. (The trap can also be triggered manually or disarmed from area **E30**.)"

  - name: "Routine"
    desc: "(1 action) Each round on its initiative count, the trap pumps more toxic gas into the room.\n\nAny breathing creature in the room takes 4d6 poison damage (a successful DC 22 Fortitude check save halves the damage taken). If a creature acts before the trap on the first round, it has the option of holding its breath to postpone taking damage from the trap-holding one's breath after the trap's first action has no effect, since the air in the creature's lungs is already tainted. Locating and blocking one of the hidden gas vents reduces the poison damage by 1d6-if all four are blocked, the trap is disabled, though the door remains locked. Otherwise, the trap functions for 1 minute before all the gas is expended and characters in the room cease taking damage, after which the trap ventilates the room for 1 additional minute."
  - name: "Reset"
    desc: "The trap must be manually rearmed by unblocking the vents or replacing the poison gas tank in area **E30**."
```

```encounter-table
name: Gas Trap
creatures:
  - 1: Gas Trap
```

