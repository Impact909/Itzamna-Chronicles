---
title: Keystone Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #182: Graveclaw
aliases: "Actor.aJ3HU4UtZAgEyMjg" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Keystone Trap"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +12, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, Keystone Hardness 15; Keystone HP 60 (BT 30);; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A 5-foot-square metal vault covered with knobs lies concealed within a stone block. A lever on the stone block slides the vault into view. When the vault is exposed-whether it's slid out or whether the stone is smashed open-the trap activates."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 24 Thievery check (trained) to find and press hidden knobs in a specific order (three successes are required to disable the trap, which also opens it); DC 24 Crafting check (expert) to sabotage the vault's mechanisms, reducing its actions by 1 (when the trap's actions are reduced to 0, it is disabled)"
attacks:
  - name: ""

  - name: "Keystone"
    desc: "passive **Keystone Hardness** 15\n\n**Keystone** HP 60 (BT 30)"

  - name: "Exposed Vault"
    desc: "`pf2:r` **Trigger** The vault is exposed\n* * *\n\n**Effect** The vault makes a poison dart spray Strike at a random creature within 30 feet. The trap then rolls initiative."

  - name: "Electrify"
    desc: "action The metal vault crackles with electricity. In air, this would damage only creatures touching it; in water, the trap deals 2d8 electricity damage to all creatures in a 10-foot emanation (DC 25 Fortitude check)."

  - name: "Launch Darts"
    desc: "action The vault fires a stream of poisoned darts. The trap attacks all creatures in a 30-foot line with its poison dart spray Strike; roll 1d8 to determine the line's direction. These Strikes don't have a multiple attack penalty."

  - name: "Spin"
    desc: "action The vault spins quickly for 1 round. While it Spins, checks to disable the trap have a -2 circumstance penalty, and it Launches Darts at all creatures within 30 feet of it, rather than in a line."
  - name: "Melee"
    desc: "Poison Dart Spray +18 (range increment 60 feet) "

  - name: "Routine"
    desc: "The keystone uses its 3 actions to Electrify, Spin, and then Launch Darts. When the trap loses an action, roll randomly to determine which action it loses."

```

```encounter-table
name: Keystone Trap
creatures:
  - 1: Keystone Trap
```

