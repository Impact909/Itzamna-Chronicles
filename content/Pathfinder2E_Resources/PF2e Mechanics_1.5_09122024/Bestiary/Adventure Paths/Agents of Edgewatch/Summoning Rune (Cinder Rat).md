---
title: Summoning Rune (Cinder Rat)
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.EWZWuHINdWcDIVMj" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Summoning Rune (Cinder Rat)"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 12
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
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
  - name: "Stealth DC 12" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An invisible cloud of magical sensors detects living creatures in the room and summons fire elementals to slay the creatures."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Acrobatics check (trained) to approach without triggering the trap, followed by DC 22 Thievery check (trained) to erase the rune or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 20) to counteract the rune"
attacks:
  - name: ""

  - name: "Summon Elementals"
    desc: "`pf2:r` (arcane, summon) **Trigger** A living creature enters the room\n* * *\n\n**Effect** Two rounds after a creature enters the room, the room's door slams shut and locks (two Thievery checks to pick), and two [[Monster Core/Cinder Rat|Cinder Rat]] fire elementals emerge from the floor.\n\nThe elementals roll initiative and remain for [[/gmr 3d6 #rounds]]{3d6 rounds}, after which the spell ends and the creatures disappear. The elementals also disappear if someone disables the trap before the duration expires.\n\nThe summoned elementals can use 3 actions each round and can use reactions, unlike most summoned creatures."


  - name: "Reset"
    desc: "The trap resets each day at dawn."
```

```encounter-table
name: Summoning Rune (Cinder Rat)
creatures:
  - 1: Summoning Rune (Cinder Rat)
```

