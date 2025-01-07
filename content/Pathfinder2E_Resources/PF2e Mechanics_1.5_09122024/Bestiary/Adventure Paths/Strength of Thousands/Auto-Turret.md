---
title: Auto-Turret
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #173: Doorway to the Red Star
aliases: "Actor.NHkoNnCkdqZnG6yG" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Auto-Turret"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 33
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +29, __Ref__ +27, "
hp: 100
health:
  - name: ""
  - name: "HP"
    desc: "100; __Hardness__ 24; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "(expert); darkvision"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A mounted gun equipped with a magical targeting system and integrated ammo supply."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 35 Thievery check (master) to disconnect the turret from its ammo supply system, or DC 35 Arcana check (master) to neutralize the magical targeting system.\n\nTan‑Takneh can also deactivate one or both auto‑turrets remotely with a special command word."
attacks:
  - name: ""

  - name: "Bullet Spray"
    desc: "`pf2:r` (attack) **Trigger** A creature comes within 60 feet of Tan-Takneh's campsite\n* * *\n\n**Effect** The turret attacks the triggering creature with a longrifle Strike."
  - name: "Melee"
    desc: "Longrifle +30 (backstabber, concussive, fatal d12, kickback) "

  - name: "Routine"
    desc: "(3 actions) With each action, the auto‑turret makes a longrifle Strike against a creature within 60 feet of Tan‑Takneh's campsite (other than Tan-Takneh). If there are no such creatures, the auto‑turret instead uses its action to sprout mechanical legs, totter 20 feet in the direction of its last target, and then plant itself into the ground again. Programmed to spread its fire around, the auto‑turret doesn't attack any creature it's already attacked in the round.\n\nAfter making 15 Strikes, the auto‑turret depletes its ammunition and automatically deactivates."

```

```encounter-table
name: Auto-Turret
creatures:
  - 1: Auto-Turret
```

