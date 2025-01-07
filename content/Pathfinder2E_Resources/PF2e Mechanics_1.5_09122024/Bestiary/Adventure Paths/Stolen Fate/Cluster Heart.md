---
title: Cluster Heart
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

source: Pathfinder #191: The Destiny War
aliases: "Actor.rKcxD4SZuAyA2UZM" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Cluster Heart"
level: "Hazard 18"


trait_01: [[environmental]]
modifier: 35
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +33, __Ref__ +27, "
hp: 300
health:
  - name: ""
  - name: "HP"
    desc: "300; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ sonic 20"
perception:
  - name: ""
  - name: "Stealth DC 45" 
    desc: "(master) to hear or feel the energy coalescing"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A wave of magic passes through the area, causing crystal shards to grow and stab intruders."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 45 Nature check (master) to chip away at the crystal and disrupt its resonance, or DC 42 Thievery check (master) to carefully detach the crystals and then safely smash them"
attacks:
  - name: ""

  - name: "Resistance to Disintegrate"
    desc: "passive [[Spells/Disintegrate|Disintegrate]] deals double damage, ignoring Hardness, rather than destroying the cluster heart outright"

  - name: "Crystal Surge"
    desc: "`pf2:r` (force) **Trigger** A non-elemental creature ends its turn adjacent to the cluster heart\n* * *\n\n**Effect** The heart extends shards of crystal imbued with force, like a jabbing blade, and deals 3d10+20 force damage and 3d10+20 piercing damage to all creatures in a 20-foot radius (DC 40 Reflex check save). A creature who takes piercing damage from the surge is exposed to crystal corruption. On a critical failure, a creature also takes 2d6 persistent bleed damage."

  - name: "Crystalline Corruption"
    desc: "passive (arcane, curse, incapacitation) Creatures afflicted by this curse slowly turn to solid crystal. This affliction's sickened, slowed, and paralyzed conditions can't be removed until the affliction itself is removed. Creatures with both the earth and elemental traits instead become carriers and suffer no ill effects aside from gaining the weakness to sonic.\n\n**Saving Throw** DC 40 Fortitude check\n\n**Stage 1** sickened 1 (1 hour)\n\n**Stage 2** weakness 5 to sonic and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** weakness 5 to sonic and [[Conditions/Slowed|Slowed 1]] (1 day)\n\n**Stage 4** weakness 10 to sonic and [[Conditions/Paralyzed|Paralyzed]] (1 day)\n\n**Stage 5** weakness 10 to sonic, and the creature is permanently [[Conditions/Petrified|Petrified]]."


  - name: "Reset"
    desc: "Once the cluster heart uses its reaction, it automatically resets after 1 minute. As long as the cluster heart has 150 or more Hit Points, it recovers 50 per day."
```

```encounter-table
name: Cluster Heart
creatures:
  - 1: Cluster Heart
```

