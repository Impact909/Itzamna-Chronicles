---
title: Summoning Rune (Cockatrice)
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #181: Zombie Feast
aliases: "Actor.raDI2adbPG9DLV6P" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Summoning Rune (Cockatrice)"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 10
sourcebook: "_Pathfinder #181: Zombie Feast_"
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
  - name: "Stealth DC 10" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A cloud of invisible magical sensors floats in the square above an invisible floor rune."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Acrobatics check to approach without triggering the trap followed by DC 20 Thievery check (trained) to disrupt the rune's summoning effect; alternatively, [[Spells/Dispel Magic|Dispel Magic]] (2nd level; counteract DC 17) to counteract the rune"
attacks:
  - name: ""

  - name: "Summon Monster"
    desc: "`pf2:r` (arcane, summon) **Trigger** A creature enters the cloud of magical sensors\n* * *\n\n**Effect** The trap summons a [[Monster Core/Cockatrice|Cockatrice]]. The cockatrice rolls initiative and remains for [[/gmr 2d6 #Summoning Duration]]{2d6 rounds}; after this duration, the spell ends and the cockatrice disappears. The cockatrice also disappears if someone disables the trap before the duration expires. The cockatrice can use 3 actions each round and can use reactions, unlike most summoned creatures."


  - name: "Reset"
    desc: "The trap resets after 24 hours."
```

```encounter-table
name: Summoning Rune (Cockatrice)
creatures:
  - 1: Summoning Rune (Cockatrice)
```

