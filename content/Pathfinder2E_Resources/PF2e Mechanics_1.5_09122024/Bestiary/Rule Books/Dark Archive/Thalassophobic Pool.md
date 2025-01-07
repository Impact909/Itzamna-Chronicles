---
title: Thalassophobic Pool
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.zDl7SFfdOTbbmUqS" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Thalassophobic Pool"
level: "Hazard 12"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 15
sourcebook: "_Pathfinder Dark Archive_"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The pool sucks in creatures that fall into it, making them sink into its endless depths."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Diplomacy check (master) or DC 32 Deception check (master) to quell the fear and calm the pool or DC 35 Intimidation check to give the pool something worse to fear; three successes required."
attacks:
  - name: ""

  - name: "Downpour"
    desc: "`pf2:r` **Trigger** A creature falls into the pool\n* * *\n\n**Effect** More water pours forth from the chalice. Creatures in the pool become [[Conditions/Clumsy|Clumsy 1]], and they can't decrease their clumsy condition so long as they remain in the pool. The trap then rolls initiative."

  - name: "Routine"
    desc: "(3 actions) Water from the chalice increases the depth of the water by 10 feet for each action. Each time this happens, creatures in the pool are pushed 10 feet down and take 1d6 bludgeoning damage. As the pool has no bottom, creatures in it can fall down indefinitely; they must [[Actions/Swim|Swim]] up to avoid drowning, but the water is especially choppy, so the Athletics DC is DC 25 Athletics check. The pool never overflows. Each successful check to Disable reduces the pool's actions by 1, and once the pool is completely Disabled, the water becomes still and the Athletics DC to Swim becomes DC 10 Athletics check."
  - name: "Reset"
    desc: "The trap resets once there are no moving creatures in it."
```

```encounter-table
name: Thalassophobic Pool
creatures:
  - 1: Thalassophobic Pool
```

