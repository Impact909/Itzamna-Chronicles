---
title: Gravehall Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder Blog
aliases: "Actor.kpRJwi9fQllqTQNj" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog"
name: "Gravehall Trap"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 12
sourcebook: "_Pathfinder Blog_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +15, __Ref__ +8, __Will__ +14"
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Immunities__  object immunities,  mental,  poison; __Weaknesses__ vitality 10"
perception:
  - name: ""
  - name: "Stealth DC 12" 
    desc: " +12"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "When a living creature crosses the midpoint of the trapped tunnel, necromantic magic partially animates the corpses buried in the walls and ceiling."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 24 Thievery check (expert) to disrupt the magical trigger before the hazard rolls initiative, or DC 18 Religion check (trained) to overwhelm the area with vitality energy and prevent the hazard from using its routine for 1 round; on the third successful Religion check, the necromantic energies are disrupted and the hazard is destroyed."
attacks:
  - name: ""

  - name: "Lunging Dead"
    desc: "`pf2:r` (divine, fear, incapacitation, mental) **Trigger** A living creature crosses the midpoint of the tunnel\n* * *\n\n**Effect** The dead reach out from the walls and ceiling, moaning and spewing writhing maggots. Creatures in the room must attempt a DC 21 Will check save. The trap then rolls initiative.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Frightened|Frightened]]\n\n**Failure** The target is [[Conditions/Frightened|Frightened 2]]. It can't reduce its frightened condition below 1 while in the trap's area.\n\n**Critical Failure** As failure, and the target is [[Conditions/Paralyzed|Paralyzed]] for 1 round."

  - name: "Routine"
    desc: "(1 action) Undead fists assail all creatures in the hall, dealing 4d6 bludgeoning damage. Creatures in the hall must attempt a DC 21 Reflex check.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target takes half damage.\n\n**Failure** The target takes full damage, and its Speeds are reduced by 10 feet (to a minimum of 5 feet) for 1 round.\n\n**Critical Failure** The target takes double damage and is [[Conditions/Immobilized|Immobilized]] for 1 round."

```

```encounter-table
name: Gravehall Trap
creatures:
  - 1: Gravehall Trap
```

