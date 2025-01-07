---
title: Wailing Crystals
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #148: Fires of the Haunted City
aliases: "Actor.iMXBTE2LTgy9nRPE" 
level: 13
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Wailing Crystals"
level: "Hazard 13"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[magical]]
modifier: 27
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +26, __Ref__ +18, "
hp: 72
health:
  - name: ""
  - name: "HP"
    desc: "72; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 27" 
    desc: "(master) or DC 37 Perception check (master) to notice what appear to be screaming ghostly faces in the crystals"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three clusters of gleaming, colorful crystals are corrupted with necromantic energy that causes them to reflect negative emotions. All three must be disabled or destroyed to negate the hazard."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Thievery check (master) to carefully fracture the crystals or DC 27 Crafting check (expert) to place objects to stop the resonance, both disabling one 5-foot patch of crystals."
attacks:
  - name: ""

  - name: "HP is 72 for each 5 foot patch"
    desc: "passive "

  - name: "Echoing Cry"
    desc: "`pf2:r` (occult) **Trigger** A living creature approaches within 20 feet of a wailing crystal.\n* * *\n\n**Effect** A despairing chorus of cries echoes off the crystals, working its way into the minds of all living creatures in Jewelgate Way Station, affecting them with [[Spells/Wave of Despair|Wave of Despair]] (7th level, DC 33 Will check save).\n\nThe hazard rolls initiative."

  - name: "Anguished Shriek"
    desc: "action (emotion, mental, occult, sonic) A shrieking, distorted face composed of writhing necromantic energy lances out of the crystals to target a random living creature within 20 feet. The target takes 4d6 mental damage and 4d6 sonic damage (DC 33 Will check save)."

  - name: "Routine"
    desc: "(3 actions) The hazard uses each action for an Anguished Shriek. The wailing crystals lose 1 action for each 5-foot patch of crystals that is broken or destroyed."
  - name: "Reset"
    desc: "The wailing crystals deactivate and reset once no living creatures are within 20 feet."
```

```encounter-table
name: Wailing Crystals
creatures:
  - 1: Wailing Crystals
```

