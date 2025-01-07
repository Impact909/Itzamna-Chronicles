---
title: Pain Milker
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - pf2eHazard

source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.PozsDv7Tb6t4LyKV" 
level: 12
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Pain Milker"
level: "Hazard 12"


trait_01: [[environmental]]
modifier: 0
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +18, "
hp: 60
health:
  - name: ""
  - name: "HP"
    desc: "60; __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 10" 
    desc: " +0"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "An eerie machine made of levers, crystals, and glowing bits of metal that, as one draws near, causes unsettling aches and pains."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check (master) to deactivate the machine, or DC 38 Perception check (expert) to decipher the proper order in which the switches and dials should be adjusted in order to power the device down harmlessly"
attacks:
  - name: ""

  - name: "Agonizing Overload"
    desc: "`pf2:r` (divine) **Trigger** The pain milker is struck hard enough to take damage, or any of its dials and levers are adjusted carelessly\n* * *\n\n**Effect** The pain milker emits a shrill whine and exudes a blast of violet light. All creatures in area B2 must attempt a DC 30 Fortitude check save. This DC is reduced by 2 if the machine is broken.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 4d10 vitality or 4d10 void damage (whichever is more harmful).\n\n**Failure** The creature takes 8d10 vitality or 8d10 void damage (whichever is more harmful) and is [[Conditions/Enfeebled|Enfeebled 1]].\n\n**Critical Failure** As failure but 16d10 vitality or 16d10 void damage and [[Conditions/Enfeebled|Enfeebled 2]]."


  - name: "Reset"
    desc: "If the augnagar still lives and at least one crystallized agony is still functional, the pain milker resets automatically in a number of rounds equal to 7 - the number of remaining crystallized agonies."
```

```encounter-table
name: Pain Milker
creatures:
  - 1: Pain Milker
```

