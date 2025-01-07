---
title: Freezing Floor
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #188: They Watched the Stars
aliases: "Actor.n0mTW2m0PyfJSEv3" 
level: 8
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #188: They Watched the Stars"
name: "Freezing Floor"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 16
sourcebook: "_Pathfinder #188: They Watched the Stars_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +13, __Ref__ +17, "
hp: 56
health:
  - name: ""
  - name: "HP"
    desc: "56, to destroy the bricks and disable the trap;; __Hardness__ 14; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 16" 
    desc: "(expert) or DC 31 Perception check (master) to notice the cold fog rising from the floor"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The white brick floor radiates ice-cold air."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 24 Thievery check (expert) to erase a rune, or [[Spells/Dispel Magic|Dispel Magic]] (3rd level; counteract DC 24) to dispel a rune; all three runes must be erased or dispelled to disable the trap."
attacks:
  - name: ""

  - name: "Cold Snap"
    desc: "`pf2:r` **Trigger** A creature steps on the white bricks\n* * *\n\n**Effect** The trap makes a frost jet Strike against the triggering creature and rolls initiative."
  - name: "Melee"
    desc: "Frost Jet +20 () No multiple attack penalty."

  - name: "Frostbite"
    desc: "passive A creature that takes persistent cold damage from the trap's frost jet Strike must attempt a DC 18 Fortitude check save.\n* * *\n\n**Critical Success** The creature isn't affected and is immune to this frostbite effect for 24 hours.\n\n**Success** The creature isn't affected.\n\n**Failure** The creature can't stop shivering and becomes [[Conditions/Clumsy|Clumsy 1]].\n\n**Critical Failure** As failure, and the creature becomes [[Conditions/Fatigued|Fatigued]]."

  - name: "Routine"
    desc: "(3 actions) With each action, the trap attempts a frost jet Strike against any creature standing on the white bricks. The trap loses 1 action per disabled or dispelled rune."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 minute."
```

```encounter-table
name: Freezing Floor
creatures:
  - 1: Freezing Floor
```

