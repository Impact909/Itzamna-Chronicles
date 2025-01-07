---
title: Lava Flume Tube
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - pf2eHazard
  - complex
source: Pathfinder Core Rulebook
aliases: "Actor.Rm5rGJWStwKP7CVG" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Core Rulebook"
name: "Lava Flume Tube"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[mechanical]]
modifier: 19
sourcebook: "_Pathfinder Core Rulebook_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +16, "
hp: 48
health:
  - name: ""
  - name: "HP"
    desc: "48, to destroy a channel gate (this prevents that channel from being disabled and stops the trap from resetting); &lt;strong&gt;Floor Hardness&lt;/strong&gt; 18; &lt;strong&gt;Floor HP&lt;/strong&gt; 72 (BT 36); __Hardness__ 12; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 19" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Four gated channels carved into stone allow lava to flow into a 15-foot-tall room; the floor can withdraw to allow the hardened lava to fall into a chamber beneath."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Thievery check (expert) to block a channel, or DC 31 Thievery check (master) to release the floor latch and escape to the chamber below"
attacks:
  - name: ""

  - name: "Flume Activation"
    desc: "`pf2:r` **Trigger** A creature tries to leave the room.\n* * *\n\n**Effect** The exits seal instantly and the trap rolls initiative."

  - name: "Routine"
    desc: "(4 actions) The trap loses 1 action per disabled channel each turn. On each action, a different channel spews lava, dealing 4d6 fire damage to each creature within 10 feet of the channel (DC 27 Reflex check), and increasing the depth of the lava in the room by 1 foot (4 feet per round if all the channels are active).\n\nA creature that starts its turn in lava takes 8d6 fire damage and is immobilized until it Escapes the hardening lava (DC 27). The creature might suffocate if covered in lava.\n\nLava from the previous round hardens fully at the start of the trap's turn, effectively raising the floor of the room. Once the room is full of lava, the trap stops taking actions, but creatures in the room remain stuck until the floor opens and the trap resets."
  - name: "Reset"
    desc: "The trap deactivates and resets after 1 hour by withdrawing the floor, cracking and dumping the hardened lava (and any creatures trapped inside) into the chamber. Creatures fall 40 feet, taking falling damage (typically 17 bludgeoning damage)."
```

```encounter-table
name: Lava Flume Tube
creatures:
  - 1: Lava Flume Tube
```

