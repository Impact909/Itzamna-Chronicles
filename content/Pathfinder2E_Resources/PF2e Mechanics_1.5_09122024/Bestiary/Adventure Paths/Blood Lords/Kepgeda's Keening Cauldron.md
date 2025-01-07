---
title: Kepgeda's Keening Cauldron
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #181: Zombie Feast
aliases: "Actor.1wxC4OiCbrRGKovC" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Kepgeda's Keening Cauldron"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 10
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +12, __Ref__ +6, __Will__ +6"
hp: 48
health:
  - name: ""
  - name: "HP"
    desc: "48; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 5"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The cauldron's ear-splitting keening calls forth spectral claws to assail ears and souls alike."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Athletics check to tip the cauldron, or DC 20 Occultism check or DC 20 Religion check (trained) to ward against the cauldron's effects. Any combination of three successful attempts is required to fully disable the haunt. When the haunt is disabled, the coven seeks vengeance."
attacks:
  - name: ""

  - name: "Crescendo of Claws"
    desc: "`pf2:r` (emotion, fear, mental) **Trigger** A creature other than Kepgeda is within 15 feet of the cauldron for at least 1 round\n* * *\n\n**Effect** The screams increase in intensity, and a torrent of phantasmal, three-fingered hands with iron claws spews from the cauldron to assail creatures in area **E13**. Each creature in the room must attempt a DC 23 Will check save, with the following results. Kepgeda is immune to the haunt's effects, as she loves the cauldron's screams. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature becomes [[Conditions/Frightened|Frightened 2]] and becomes [[Conditions/Off-Guard|Off-Guard]] as long as they remain frightened.\n\n**Critical Failure** The creature becomes [[Conditions/Frightened|Frightened 3]] and is [[Conditions/Grabbed|Grabbed]] as long as they remain frightened."

  - name: "Routine"
    desc: "(1 action) The spectral hands scurry about, grabbing at all of Kepgeda's foes in area **E13**. Each such creature takes 3d6 mental damage (DC 20 Will check) as the spectral claws assail them. A creature that takes mental damage from this effect doesn't reduce their frightened value at the end of their next turn."
  - name: "Reset"
    desc: "The haunt becomes inert (resuming its usual screaming) at the end of any round in which no creatures other than Kepgeda remain in her kitchen."
```

```encounter-table
name: Kepgeda's Keening Cauldron
creatures:
  - 1: Kepgeda's Keening Cauldron
```

