---
title: Arms of the Drowned
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #197: Let the Leaves Fall
aliases: "Actor.F7qVO90If0Pp9cvo" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #197: Let the Leaves Fall"
name: "Arms of the Drowned"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 20
sourcebook: "_Pathfinder #197: Let the Leaves Fall_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +12, "
hp: 46
health:
  - name: ""
  - name: "HP"
    desc: "46; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert) to catch glimpses of ghostly figures drowning in the water below."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Ghostly arms rise up from the water to clutch and grab, while a geyser of leech-infested water sprays up into the central shrine."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 20 Religion check to offer prayers to calm the haunt, or DC 23 Intimidation check to threaten the unquiet spirits away"
attacks:
  - name: ""

  - name: "Rising Waters"
    desc: "`pf2:r` **Trigger** A creature swims more than halfway across the river, ends their turn in the bridge shrine, or sets foot onto the northern bridge\n* * *\n\n**Effect** Ghostly arms rise up from the river to grab and shake both bridges. Creatures standing on the bridge must attempt a DC 20 Reflex check save or be knocked [[Conditions/Prone|Prone]]. A blast of river water sprays up inside the shrine to deposit two brood leech swarms in the shrine. The haunt and the leech swarms then roll initiative."
  - name: "Melee"
    desc: "Ghostly Arms +12 () **Effect** grapple"

  - name: "Routine"
    desc: "(3 actions) Ghostly arms flail about and attempt to grab creatures in the shrine or on either bridge. Each round, the haunt uses 3 actions to attempt to grapple a PC on the bridge or in the shrine. If a PC is [[Conditions/Restrained|Restrained]], the haunt can use one of its actions to drag a PC into the river. A PC who's restrained in the river risks drowning."
  - name: "Reset"
    desc: "The haunt deactivates and resets at the start of any round in which the PCs aren't in the river, on the bridges, or in the shrines, but the leech swarms remain in the shrine for 10 minutes before retreating back into the water below."
```

```encounter-table
name: Arms of the Drowned
creatures:
  - 1: Arms of the Drowned
```

