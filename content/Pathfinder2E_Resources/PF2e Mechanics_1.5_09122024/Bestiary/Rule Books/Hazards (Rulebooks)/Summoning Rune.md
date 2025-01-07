---
title: Summoning Rune
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder GM Core
aliases: "Actor.x7OQAki9RCsiiaK6" 
level: 1
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder GM Core"
name: "Summoning Rune"
level: "Hazard 1"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 7
sourcebook: "_Pathfinder GM Core_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 7" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A cloud of invisible magical sensors in a 10-foot radius surrounds an invisible wall or floor rune the size of the creature to be summoned."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 15 Acrobatics check to approach without triggering the trap followed by DC 17 Thievery check (trained) to erase the rune, or [[Spells/Dispel Magic|Dispel Magic]] (1st rank; counteract DC 15) to counteract the rune"
attacks:
  - name: ""

  - name: "Summon Monster"
    desc: "`pf2:r` (arcane, summon) **Trigger** A creature enters the cloud of magical sensors\n* * *\n\n**Effect** This trap summons a specific 1st-level creature, determined when the trap is created. The creature rolls initiative and remains for 2d6 rounds, after which the spell ends and the creature disappears. The creature also disappears if someone disables the trap before the duration expires. The summoned creature can use 3 actions each round and can use reactions, unlike most summoned creatures."


  - name: "Reset"
    desc: "The trap resets each day at dawn."
```

```encounter-table
name: Summoning Rune
creatures:
  - 1: Summoning Rune
```

