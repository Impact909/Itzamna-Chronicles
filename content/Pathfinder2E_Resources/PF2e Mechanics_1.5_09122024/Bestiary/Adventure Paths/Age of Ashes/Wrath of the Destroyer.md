---
title: Wrath of the Destroyer
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #146: Cult of Cinders
aliases: "Actor.BVwbeE39DTOYHDaY" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Wrath of the Destroyer"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 22
sourcebook: "_Pathfinder #146: Cult of Cinders_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +14, "
hp: 72
health:
  - name: ""
  - name: "HP"
    desc: "72; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 22" 
    desc: "(expert) to notice subtle vapors of magical energy seething across the doors"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "These heavy doors, carved with an image of Dahak, echo with a hatred so powerful that it can kill anyone who comes nearby, manifesting a vision of Dahak's head emerging from the doors to strike at a foe."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Thievery check (expert) to disrupt the divine magic, DC 29 Religion check (expert) to placate the wrathful energies, or [[Spells/Dispel Magic|Dispel Magic]] (5th level; counteract DC 26)."
attacks:
  - name: ""

  - name: "Expunge"
    desc: "`pf2:r` **Trigger** A non-worshipper of Dahak touches either door leading to **C7**\n* * *\n\n**Effect** The hazard targets the creature with Face of the Fatal Divine, then rolls initiative."

  - name: "Face of the Fatal Divine"
    desc: "action (death, divine, emotion, fear, illusion, mental) The creature beholds the face of Dahak as it emerges to bite with its burning jaws, targeting the creature with [[Spells/Phantasmal Killer|Phantasmal Killer]] (5th level, DC 29 Will check)."

  - name: "Routine"
    desc: "(1 action) On its initiative, the wrath of the destroyer targets the closest target in area **C6** with Face of the Fatal Divine."
  - name: "Reset"
    desc: "The trap deactivates and resets if 1 minute passes without any creature being in range."
```

```encounter-table
name: Wrath of the Destroyer
creatures:
  - 1: Wrath of the Destroyer
```

