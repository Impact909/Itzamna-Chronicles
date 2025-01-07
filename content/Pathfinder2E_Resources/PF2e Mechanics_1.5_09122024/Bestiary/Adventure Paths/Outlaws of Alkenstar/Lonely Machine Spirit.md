---
title: Lonely Machine Spirit
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #178: Punks in a Powder Keg
aliases: "Actor.CY7rWYSrvLWNueGy" 
level: 3
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Lonely Machine Spirit"
level: "Hazard 3"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 13
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +8, "
hp: 44
health:
  - name: ""
  - name: "HP"
    desc: "44; __Hardness__ 11; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ electricity 5, orichalcum 5, vitality 5"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Ghostly smoke rising from an alchemical engine belches forth; the screeching sound of grinding gears echoes from the engine as it shutters to life."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 22 Religion check (trained) or DC 20 Engineering check Lore (trained) to eject the animating spirit from its mechanical shell. Creatures gain a +2 circumstance bonus on their check if they use the airship's name, Harpy's Kiss, as part of their skill check, or a +4 circumstance bonus if they utter the name \"Phera Wyndslow.\" The haunt remains active until its spirit is ejected, the haunt is destroyed, or there are no living creatures within 30 feet."
attacks:
  - name: ""

  - name: "Painful Whistle"
    desc: "`pf2:r` (sonic) **Trigger** A living creature approaches within 10 feet of the engine (marked with a \"T\" on the map)\n* * *\n\n**Effect** A loud whistle blows and all creatures within 30 feet take 2d6 sonic damage and become [[Conditions/Stunned|Stunned 1]] (DC 20 Fortitude check; creatures aren't stunned on a success). The lonely machine spirit then rolls initiative."

  - name: "Belch Smoke"
    desc: "action (air, fire) The airship's engine issues forth a cloud of alchemical smoke in a 30-foot cone. Creatures within the cone must attempt a DC 20 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d6 poison damage and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes 2d6 poison damage and is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature takes 3d6 poison damage and is sickened 2."
  - name: "Melee"
    desc: "Red hot gear +12 (fire, range 10 feet) "

  - name: "Routine"
    desc: "(2 actions) The lonely machine spirit Belches Smoke or makes two red hot gear Strikes against two creatures within 30 feet."
  - name: "Reset"
    desc: "The haunt deactivates and resets after 1 hour."
```

```encounter-table
name: Lonely Machine Spirit
creatures:
  - 1: Lonely Machine Spirit
```

