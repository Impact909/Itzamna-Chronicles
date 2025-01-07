---
title: Darkside Mirror
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Core Rulebook
aliases: "Actor.8jkYErnoERjk3OIz" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Core Rulebook"
name: "Darkside Mirror"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 24
sourcebook: "_Pathfinder Core Rulebook_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +25, __Ref__ +20, "
hp: 4
health:
  - name: ""
  - name: "HP"
    desc: "4, The mirror can&#x27;t be damaged while any mirror duplicate is alive; __Hardness__ 1; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 24" 
    desc: "(master) to notice it isn't a regular mirror"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A magic mirror replaces characters with evil mirror duplicates from another dimension."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 34 Thievery check (legendary) to retrieve a creature from the other dimension within 10 minutes of the switch (possible only if their mirror duplicate is dead), DC 39 Thievery check (master) to permanently disable the mirror once all mirror duplicates are dead, or [[Spells/Dispel Magic|Dispel Magic]] (7th level; counteract DC 32) to counteract the mirror for 1 minute and prevent additional replacements during that time"
attacks:
  - name: ""

  - name: "Reflection of Evil"
    desc: "`pf2:r` (arcane, teleportation) **Trigger** A non-evil creature is reflected in the mirror.\n* * *\n\n**Effect** The mirror absorbs the creature into the mirror, replacing it with an evil mirror duplicate (DC 34 Reflex check to avoid being absorbed into the mirror), and rolls initiative."

  - name: "Routine"
    desc: "(1 action) The mirror absorbs another reflected creature into the mirror and replaces it with a mirror duplicate. Mirror duplicates attack on their own initiative, using the same statistics as the original creature, but with an evil alignment (changing only abilities that shift with the alignment change). A mirror duplicate can spend 3 actions in contact with the mirror to return to its original dimension and release the creature it duplicated, but most mirror duplicates prefer not to."
  - name: "Reset"
    desc: "The mirror is always ready to absorb creatures into the other dimension. Ten minutes after a creature is sucked into the mirror, if an ally doesn't rescue the creature with Thievery, it reaches the other dimension, where it might be captured or killed. In the mirror dimension, it counts as a mirror duplicate, so the denizens of the other dimension can't destroy the mirror on their side while the absorbed creature is there. These dimensions are alternate realities, not planes, so even rituals like _plane shift_ can't reach them."
```

```encounter-table
name: Darkside Mirror
creatures:
  - 1: Darkside Mirror
```

