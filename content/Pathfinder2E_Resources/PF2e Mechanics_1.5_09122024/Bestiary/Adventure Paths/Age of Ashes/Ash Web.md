---
title: Ash Web
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - fungus
  - pf2eHazard

source: Pathfinder #148: Fires of the Haunted City
aliases: "Actor.5CEBiT4L2vhMArAL" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Ash Web"
level: "Hazard 10"


trait_01: [[environmental]]
trait_02: [[fungus]]
modifier: 21
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +22, __Ref__ +14, "
hp: 100
health:
  - name: ""
  - name: "HP"
    desc: "100; __Immunities__  object immunities,  acid,  critical hits,  electricity,  fire,  precision"
perception:
  - name: ""
  - name: "Stealth DC 31" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "This dangerous sooty black mold readily releases its toxic spores when disturbed. The entire swath of fungus in area **B2** is a single organism. There are nine 10-foot-square patches to remove, but the whole organism dies once it takes enough damage."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 27 Survival check (expert) to remove a 10-foot-square patch of ash web without triggering the spores"
attacks:
  - name: ""

  - name: "Spore Explosion"
    desc: "`pf2:r` **Trigger** A creature moves into the ash web's space or damages the web with any type of damage other than cold damage.\n\n**Requirements** The ash web is not in direct sunlight.\n* * *\n\n**Effect** The triggering creature and all creatures within 10 feet of that creature are exposed to ash web spores."

  - name: "Ash Web Spores"
    desc: "passive (inhaled, poison) The enfeebled condition from ash web remains even after the poison's duration ends. The condition's value reduces by 1 per hour. Gugs are immune to this poison; instead, they have vivid and strange dreams when they sleep after ingesting ash web.\n\n**Saving Throw** DC 29 Fortitude check\n\n**Maximum Duration** 6 rounds\n* * *\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 4d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)\n\n**Stage 3** 6d6 poison damage and [[Conditions/Enfeebled|Enfeebled 3]] (1 round)."


  - name: "Reset"
    desc: "This large patch of ash web resets automatically at the start of the round."
```

```encounter-table
name: Ash Web
creatures:
  - 1: Ash Web
```

