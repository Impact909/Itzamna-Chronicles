---
title: Night's Breath Trap
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard

source: Pathfinder #184: The Ghouls Hunger
aliases: "Actor.4F2oGtf96HLYIccJ" 
level: 14
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Night's Breath Trap"
level: "Hazard 14"


trait_01: [[magical]]
trait_02: [[trap]]
modifier: 28
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +28, __Ref__ +22, "
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90; __Hardness__ 22; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 38" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The night giant mummy unfolds its arms and leans forward to exhale a blast of gray mist and shrieking spirits into the room."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 33 Thievery check to \"blind\" the statue so that it cannot notice any who approach, DC 35 Occultism check to redirect and expend the trap's occult energies harmlessly, or [[Spells/Dispel Magic|Dispel Magic]] (7th level, counteract DC 32) to counteract the trap."
attacks:
  - name: ""

  - name: "Night's Breath"
    desc: "`pf2:r` (emotion, fear, illusion, mental, occult) **Trigger** A Small or larger creature in area **A2** moves within 15 feet of the secret door to the north or the double door to area **A5**\n* * *\n\n**Effect** The mummy exhales a blast of gray mist into the room that imparts an overwhelming sense that night itself is consuming all thought. The trap deals 12d6 mental damage to all creatures in area **A2**, who each must attempt a DC 36 Will check saving throw.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes full damage, is [[Conditions/Frightened|Frightened 2]], and is [[Conditions/Fleeing|Fleeing]] for as long as they remain frightened.\n\n**Critical Failure** The creature takes double damage, is [[Conditions/Frightened|Frightened 3]], and is fleeing for as long as they remain frightened."


  - name: "Reset"
    desc: "The trap resets during the following round, after which it can be triggered again."
```

```encounter-table
name: Night's Breath Trap
creatures:
  - 1: Night's Breath Trap
```

