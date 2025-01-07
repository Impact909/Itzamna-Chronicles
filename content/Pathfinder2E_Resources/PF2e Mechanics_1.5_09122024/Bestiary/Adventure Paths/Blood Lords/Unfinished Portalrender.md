---
title: Unfinished Portalrender
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.goOtkB5u6lE4L3q3" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Unfinished Portalrender"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 27
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +20, "
hp: 88
health:
  - name: ""
  - name: "HP"
    desc: "88; __Hardness__ 22; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A sphere of concentrated agony harvested from a qlippoth begins pulsing with violet light as it blasts the room with otherworldly agony."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 37 Thievery check (master) to dismantle the housing and refocus the agony inward so it consumes itself harmlessly, DC 33 Arcana check or DC 33 Occultism check (master) to vent the agony in a controlled way that causes the portalrender to become inert after 1 minute (during which it can still be triggered normally), or [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 31)"
attacks:
  - name: ""

  - name: "Agonizing Pulse"
    desc: "`pf2:r` (emotion, mental, occult) **Trigger** The unfinished portalrender takes any damage or is moved (the portalrender is Bulk 5)\n* * *\n\n**Effect** The central sphere of concentrated agony flashes bright violet, filling the mind's of the room's inhabitants with overwhelming mental sensations of pain and hallucinations that the world around them is being torn away and replaced by a demon-haunted apocalypse. All creatures in area **B4** must attempt a DC 33 Will check save, then the trap rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d6 mental damage from the pain.\n\n**Failure** The creature takes 8d6 mental damage from the pain and is [[Conditions/Confused|Confused]] until the end of their next turn.\n\n**Critical Failure** The creature takes 16d6 mental damage from the pain, is [[Conditions/Stupefied|Stupefied 1]], and is confused for 1 minute."

  - name: "Routine"
    desc: "The unfinished portalrender continues to flood area **B4** with agony, and everyone in the room must attempt a DC 33 Will check save against its Agonizing Pulse. At the end of its turn, the unfinished portalrender attempts a DC 6 Flat check. On a failure, its stores of agony deplete and it deactivates, causing the central orb of agony to fade away permanently."

```

```encounter-table
name: Unfinished Portalrender
creatures:
  - 1: Unfinished Portalrender
```

