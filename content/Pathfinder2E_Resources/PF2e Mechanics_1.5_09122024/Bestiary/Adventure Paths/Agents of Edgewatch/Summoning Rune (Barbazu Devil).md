---
title: Summoning Rune (Barbazu Devil)
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #157: Devil at the Dreaming Palace
aliases: "Actor.RdkPSIDXweO3OqxF" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Summoning Rune (Barbazu Devil)"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 11
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
  - name: "Stealth DC 11" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A summoning circle inlaid into the room's floor detects living creatures and summons a violent devil."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Perception check to notice the trap's magic and avoid stepping on the floor outside the circle, followed by DC 21 Thievery check (trained) to break the circle or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 23) to counteract the rune"
attacks:
  - name: ""

  - name: "Summon Devil"
    desc: "`pf2:r` (arcane, summon) **Trigger** A living creature steps on any part of the floor not enclosed by the summoning circle\n* * *\n\n**Effect** One round after a creature touches the triggering area, the door to the room slams shut and locks (two Thievery checks to pick) and a [[Bestiary 1/Barbazu|Barbazu]] devil appears in the summoning circle.\n\nThe devil rolls initiative and remains for 3d6 rounds, after which the spell ends and the devil disappears. The devil also disappears if someone disables the trap before the duration expires.\n\nThe summoned devil can use 3 actions each round and can use reactions, unlike most summoned creatures."


  - name: "Reset"
    desc: "The trap resets each day at dawn."
```

```encounter-table
name: Summoning Rune (Barbazu Devil)
creatures:
  - 1: Summoning Rune (Barbazu Devil)
```

