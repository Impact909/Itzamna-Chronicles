---
title: Imperious Darkside Mirror
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #155: Lord of the Black Sands
aliases: "Actor.wb5nfIMiDnjS7uo2" 
level: 19
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Imperious Darkside Mirror"
level: "Hazard 19"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 32
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +32, __Ref__ +27, "
hp: 4
health:
  - name: ""
  - name: "HP"
    desc: "4, The mirror can&#x27;t be damaged while any mirror duplicate is alive; __Hardness__ 1; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(legendary) to notice that the mirror isn't a regular mirror"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "This magic mirror replaces characters with evil duplicates from another dimension."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 42 Thievery check (legendary) to retrieve a creature from the mirror within 10 minutes of the switch (possible only if their mirror duplicate is dead), DC 47 Thievery check (master) to permanently disable the mirror once all mirror duplicates are dead, or [[Spells/Dispel Magic|Dispel Magic]] (9th level; counteract DC 40) to counteract the mirror for 1 minute and prevent additional replacements from appearing during that time."
attacks:
  - name: ""

  - name: "Reflection of Evil"
    desc: "`pf2:r` (arcane, teleportation) **Trigger** A non-evil creature is reflected in the mirror\n* * *\n\n**Effect** The mirror absorbs the creature into the mirror, replacing it with an evil mirror duplicate (DC 42 Reflex check to avoid being absorbed into the mirror), and rolls initiative."

  - name: "Routine"
    desc: "(1 action) The mirror absorbs another reflected creature into the mirror (DC 42 Reflex check) and replaces it with a mirror duplicate. Mirror duplicates act on their own initiative, using the same statistics as the original creature, but with an evil alignment (changing only abilities that shift with the alignment change).\n\nMirror duplicates are legendary in Intimidation and are permanently [[Conditions/Quickened|Quickened]], but they can use this additional action only to Demoralize.\n\nA mirror duplicate can spend 3 actions in contact with the mirror to return to its original dimension and release the creature it duplicated, but most mirror duplicates prefer not to."
  - name: "Reset"
    desc: "The mirror is always ready to absorb creatures into another dimension. 10 minutes after a creature is sucked into the mirror, if an ally doesn't rescue the creature using the Thievery skill, the creature reaches the mirror dimension, where it could be captured or killed. In the mirror dimension, it counts as a mirror duplicate, so the denizens of the other dimension can't destroy the mirror on their side while the absorbed creature is there. These dimensions are alternate realities, not planes, so even rituals like [[Spells/Interplanar Teleport|Interplanar Teleport]] can't reach them."
```

```encounter-table
name: Imperious Darkside Mirror
creatures:
  - 1: Imperious Darkside Mirror
```

