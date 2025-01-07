---
title: Waxworks Onslaught Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #160: Assault on Hunting Lodge Seven
aliases: "Actor.w8OytYgyjHnXQcmI" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Waxworks Onslaught Trap"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 27
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +25, "
hp: 104
health:
  - name: ""
  - name: "HP"
    desc: "104, to destroy a tub and prevent it from making any further attacks; &lt;strong&gt;Door Seal Hardness&lt;/strong&gt; 18; &lt;strong&gt;Door Seal HP&lt;/strong&gt; 72 (BT 36) to destroy the wax on a sealed door and allow anyone to escape through the door; __Hardness__ 25; __Immunities__  object immunities,  critical hits,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four huge tubs containing congealed wax, enchanted to melt and envelop unwary intruders, each sit atop a cold fire."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to drain the wax from a tub or DC 45 Athletics check (master) to push through the wax blocking a sealed door and escape (other creatures must push their own way through, as the wax reseals)"
attacks:
  - name: ""

  - name: "Seal Room"
    desc: "`pf2:r` **Trigger** A creature comes within 5 feet of a tub\n* * *\n\n**Effect** The fires beneath the vats blaze to life, magically melting the wax in the tubs. The tubs emit gouts of wax over the room's exits, sealing them shut. The trap then rolls initiative."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action each turn per drained or destroyed tub. On each action, a different tub spews hot wax at a random creature in the room, dealing 3d12 fire damage to the target and all adjacent creatures (DC 35 Reflex check). On a failure or critical failure, the creature is also encased in hot wax. A creature that starts its turn encased in wax takes 8d12 fire damage and is immobilized until it Escapes the hardening wax (DC 35). Each turn it remains encased, the damage dealt by the hot wax decreases by 2d12 but the DC to Escape increases by 2 (minimum 0 damage, maximum DC 43). A creature that can't get free from the wax might suffocate."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 hour. At that time, the wax in the tubs cools and congeals, and any wax elsewhere in the room magically goes back into the tubs."
```

```encounter-table
name: Waxworks Onslaught Trap
creatures:
  - 1: Waxworks Onslaught Trap
```

