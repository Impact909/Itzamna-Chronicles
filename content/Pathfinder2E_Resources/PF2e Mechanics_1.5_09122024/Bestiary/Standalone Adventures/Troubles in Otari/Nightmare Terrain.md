---
title: Nightmare Terrain
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder Adventure: Troubles in Otari
aliases: "Actor.dLch4b3NtutRKfv9" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Troubles in Otari"
name: "Nightmare Terrain"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 16
sourcebook: "_Pathfinder Adventure: Troubles in Otari_"
perception:
  - name: ""
  - name: "Stealth DC 16" 
    desc: "DC 22 Perception check to detect the subtle magical aura of the land"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "What seems like an innocent stretch of land assaults trespassers with terrible illusions."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Arcana check, DC 22 Nature check, DC 22 Occultism check, or DC 22 Religion check (by a hero with expert proficiency in that skill) three times to temporarily disrupt the magic, or [[Spells/Dispel Magic|Dispel Magic]] (3rd-level spell, DC 25)"
attacks:
  - name: ""

  - name: "Step into Nightmares"
    desc: "`pf2:r` (illusion, mental, occult) If a creature that can see moves 10 feet into the affected area, the hazard rolls Stealth (+16) for its initiative."

  - name: "Routine"
    desc: "(1 action) Terrible visions assail the minds of all creatures who can see within the affected area. Each creature must attempt a DC 24 Will check saving throw.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Failure** The creature takes 2d8+9 mental damage and is [[Conditions/Frightened|Frightened 3]].\n\n**Critical Failure** The creature takes 4d8+18 mental damage and is [[Conditions/Frightened|Frightened 4]]."
  - name: "Reset"
    desc: "The terrible visions cease after all creatures have left the affected area, but the hazard is immediately ready to inflict its visions on the next creature to enter."
```

```encounter-table
name: Nightmare Terrain
creatures:
  - 1: Nightmare Terrain
```

