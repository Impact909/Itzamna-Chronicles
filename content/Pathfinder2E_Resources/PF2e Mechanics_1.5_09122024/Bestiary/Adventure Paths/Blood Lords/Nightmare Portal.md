---
title: Nightmare Portal
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.PVtUnAIIC6xZKfGT" 
level: 16
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Nightmare Portal"
level: "Hazard 16"

trait_06: "Complex"
trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 32
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +25, "
hp: 104
health:
  - name: ""
  - name: "HP"
    desc: "104; __Hardness__ 26; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Horrific visions of a lumbering monstrosity whose face is nothing but a fanged mouth lurch out of the violet mist to attempt to eat the viewer alive."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Thievery check (master) to focus the portal's energies back in on itself to close it off, or DC 36 Occultism check (master) to invoke the proper chant and make the proper hand gestures to untether the portal from the Dreamlands, or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 34) to counteract the portal for 1 minute and prevent Orgesh's influence from reaching through during that time"
attacks:
  - name: ""

  - name: "Dreadful Vision"
    desc: "`pf2:r` (illusion, mental, occult) **Trigger** At the start of a round after a creature who can dream and isn't immune to sleep effects enters the room, the portal starts to glow with purple mist. At this point, the portal triggers as soon as such a creature looks into it. A character who just passes by and doesn't specifically avert their gaze must attempt a DC 11 Flat check to not accidently glance into the portal, while a character who Searches this room automatically looks into it unless they specify otherwise.\n\n**Effect** The nightmare portal casts [[Spells/Phantasmal Calamity|Phantasmal Calamity]] (heightened to 8th level, DC 37 Will check), making reality appear to crumble away to reveal a vast cavern filled with bones through which immense wormlike creatures burrow as they endlessly eat away at the world. The trap then rolls initiative."

  - name: "Routine"
    desc: "(2 actions) A vision of an immense lumbering figure with nothing but a circular mouth for a face lurches out of the portal. For each action, the nightmare portal casts [[Spells/Phantasmal Killer|Phantasmal Killer]] (heightened to 8th level, DC 38 Will check), targeting a different creature both times. It can select targets in area **E11**, the secret alcove to the northeast, or up to 10 feet east from the door (although a closed door blocks it), choosing the closest two targets each round. The nightmare portal loses 1 action if it's broken and can thus only cast _phantasmal killer_ once per round."
  - name: "Reset"
    desc: "The nightmare portal resets 1 minute after it no longer detects targets."
```

```encounter-table
name: Nightmare Portal
creatures:
  - 1: Nightmare Portal
```

