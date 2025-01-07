---
title: Hall Of Fiery Doom
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #177: Burning Tundra
aliases: "Actor.x9Sf0DyPwrL229Rx" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Hall Of Fiery Doom"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 32
sourcebook: "_Pathfinder #177: Burning Tundra_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 0
health:
  - name: ""
  - name: "HP"
    desc: "0; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "While the roof is on fire and collapsing timbers crush those within the hall, demons fly down from the sky to pluck victims from the flames."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Two DC 32 Athletics check or DC 32 Diplomacy check checks to douse the flames; Athletics to do the work yourself or Diplomacy to muster the ghostly soldiers. This reduces the hazard's actions by 1 and prevents it from using Burning Timbers. Banish the demons with up to two DC 35 Arcana check, DC 35 Occultism check, or DC 35 Religion checkchecks; each success reduces the hazard's actions by 1, and two successes prevent it from using Demonic Abduction. When the hazard loses all 3 actions, Burning Timbers, and Demonic Abduction, it's disabled."
attacks:
  - name: ""

  - name: "Burst of Fire"
    desc: "`pf2:r` **Trigger** A creature enters the hall or ends its turn in the hall\n* * *\n\n**Effect** The hall bursts into flame, dealing 4d6 fire damage to each creature in the hall. The haunt then rolls initiative."

  - name: "Burning Timbers"
    desc: "action Creatures within the 30-foot by 90-foot area of the hall take 4d6+12 fire damage (DC 29 Reflex check)."
  - name: "Melee"
    desc: "Demonic Abduction +23 () Spectral demons lift a single creature 50 feet into the air and drop it. The haunt makes a Strike against the creature with a +23 attack bonus. On a success, the creature is lifted into the air and dropped, taking 25 bludgeoning, though it might negate some or all this damage using a spell, such as [[Spells/Gentle Landing|Gentle Landing]]. On a critical hit, the creature also takes 2d12+13 slashing damage as the demons' claws tear through its flesh."

  - name: "Routine"
    desc: "(3 actions) The haunt spends 1 action to fill the hall with burning timbers falling from above, and 2 actions to pluck up random victims and drop them to their deaths."
  - name: "Reset"
    desc: "The hall falls quiet for 24 hours, after which it can trigger again."
```

```encounter-table
name: Hall Of Fiery Doom
creatures:
  - 1: Hall Of Fiery Doom
```

