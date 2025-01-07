---
title: Maggot Pit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - environmental
  - unholy
  - pf2eHazard
  - complex
source: Pathfinder #191: The Destiny War
aliases: "Actor.dXOMqWr3vwh8ct1o" 
level: 18
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Maggot Pit"
level: "Hazard 18"

trait_06: "Complex"
trait_01: [[environmental]]
trait_02: [[unholy]]
modifier: 0
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +27, __Ref__ +33, "
hp: 120
health:
  - name: ""
  - name: "HP"
    desc: "120; __Immunities__  object immunities,  precision; __Weaknesses__ area damage 15, holy 15, splash damage 15; __Resistances__ bludgeoning 10, piercing 20, slashing 20"
perception:
  - name: ""
  - name: "Stealth DC 0" 
    desc: "(the maggots are slow and impossible to miss)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Countless human-faced, fanged maggots wriggle and squirm in this chamber."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "Three DC 45 Religion check checks within the room to utter prayers, which calm and quell the maggots with invocations to the gods"
attacks:
  - name: ""

  - name: "Damning Swarm"
    desc: "`pf2:r` (death, divine) **Trigger** a creature appears in area **M1**\n* * *\n\n**Effect** The swarming maggots squirm into a biting frenzy, and all creatures on the ground in area **M1** must attempt a DC 40 Fortitude check save. The hazard then rolls initiative.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d10+5 piercing damage, 3d6 poison damage, and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes 2d10+10 piercing damage, 6d6 poison damage, is sickened 1, and is [[Conditions/Enfeebled|Enfeebled 1]] by the maggots' bites.\n\n**Critical Failure** The creature takes 4d10+20 piercing damage, 12d6 poison damage, is sickened 1, and is [[Conditions/Enfeebled|Enfeebled 2]] by the maggots' bites."
  - name: "Melee"
    desc: "Maggot Tendril +35 (reach 200 feet) On a critical hit, the target is [[Conditions/Enfeebled|Enfeebled 1]]; this has the poison trait"

  - name: "Routine"
    desc: "(2 actions; death, divine, necromancy) On its initiative, the pit uses its first action to use Damning Swarm against any creature within 5 feet of the pit floor. It then takes its second action to form a long, thrashing tendril composed of thousands of maggots to lash at a single target within area **M1**."
  - name: "Reset"
    desc: "The pit functions continuously. If it's disabled or destroyed, it resets automatically after 24 hours if the crystal stele in area **M2** still functions, otherwise it doesn't reset."
```

```encounter-table
name: Maggot Pit
creatures:
  - 1: Maggot Pit
```

