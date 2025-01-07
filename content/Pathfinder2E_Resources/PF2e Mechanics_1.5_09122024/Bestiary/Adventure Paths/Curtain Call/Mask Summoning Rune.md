---
title: Mask Summoning Rune
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #206: Bring the House Down
aliases: "Actor.8nq2K8P8fqYthVtd" 
level: 16
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Mask Summoning Rune"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 32
sourcebook: "_Pathfinder #206: Bring the House Down_"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A cloud of invisible sensors in a 10-foot-radius surrounds an invisible floor rune."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Acrobatics check to approach a rune without triggering it followed by DC 42 Thievery check (master) to erase the rune, or [[Spells/Dispel Magic|Dispel Magic]] (8th rank, counteract DC 34) to counteract the rune."
attacks:
  - name: ""

  - name: "Summon Mask"
    desc: "`pf2:r` (divine) **Trigger** A creature enters the cloud of magical sensors\n* * *\n\n**Effect** The rune causes a chain reaction throughout the room, causing all remaining active summoning runes in area **D2** to summon a Mask of Gray Master. The masks roll initiative and remain for 12 rounds, after which the effect ends and any remaining Masks disappear. A Mask also disappears if someone disables its linked trap before the duration expires. The Mask can use 3 actions each round and can use reactions, unlike most summoned creatures."


  - name: "Reset"
    desc: "The trap resets each day at dawn."
```

```encounter-table
name: Mask Summoning Rune
creatures:
  - 1: Mask Summoning Rune
```

