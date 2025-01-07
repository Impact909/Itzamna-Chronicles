---
title: Boneburst
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - unholy
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder War of Immortals
aliases: "Actor.CprSi1OjF2MYCNd6" 
level: 14
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder War of Immortals"
name: "Boneburst"
level: "Hazard 14"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[unholy]]
modifier: 28
sourcebook: "_Pathfinder War of Immortals_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +30, __Ref__ +28, "
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90, (BT 45); __Hardness__ 20; __Immunities__  critical hits,  object immunities,  precision"
perception:
  - name: ""
  - name: "Stealth DC 28" 
    desc: "(master) to notice that clouds of debris are coalescing into swirling, faceless shapes held together by rust-red fog and spectral, dripping clots of gore"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A low howl rises from the ground, gathering strength as scraps of ancient armor, bone fragments, and clumps of earth rise into the air. Crimson vapor holds the faceless shape together, never coalescing into an identifiable form, but merely writhing through ever-changing images of torment and destruction."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 38 Occultism check (master) to temporarily negate the psychic resonances around each fragment, causing the agglomeration to fall apart, or DC 33 Religion check (expert) to temporarily interrupt Verex-That-Was's unholy power with divine energy from another source. If a boneburst takes 40 points of damage from a single source and it isn't destroyed, it is rendered dormant for 1 round."
attacks:
  - name: ""

  - name: "Gathering Mist"
    desc: "`pf2:r` **Trigger** A living creature approaches within 50 feet of a dormant boneburst\n* * *\n\n**Effect** The boneburst awakens, roiling up from the ground, and rolls initiative."

  - name: "Routine"
    desc: "(2 actions) An awakened boneburst occupies a 20-foot square; it is reduced to a 10-foot square when it reaches its BT. It can occupy the same space as other creatures, but not other bonebursts. On its initiative, the boneburst Flies up to 30 feet toward the nearest living creature as its first action. As its second action, the boneburst then coalesces around any living creature within its space, invisible shards of bone tearing at their flesh. Each living creature in its space takes 2d10+18 slashing damage and 1d10 spirit damage (DC 35 Reflex check save). If no living creatures are within its space, the boneburst can use its second action to Fly up to 30 feet."
  - name: "Reset"
    desc: "If the boneburst spends 5 consecutive rounds without coalescing around a living creature, it falls dormant, sinking back into the earth. After it falls dormant or is disabled, the boneburst gathers energy over the course of the next hour, after which it can be triggered again."
```

```encounter-table
name: Boneburst
creatures:
  - 1: Boneburst
```

