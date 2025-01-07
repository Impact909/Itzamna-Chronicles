---
title: "Sea Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.y7Dz6R7sSPLu8eTX" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Sea Drake"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Sea Drake"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[water]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +16, Stealth: +12"
abilityMods: [6, 2, 4, -1, 2, 0]
speed: 15 feet,  fly 40 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +14, __Will__ +12"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95; __Immunities__  electricity,  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Electrified Blood"
    desc: "`pf2:r` (electricity) **Trigger** An adjacent creature deals piercing or slashing damage to the sea drake\n* * *\n\n**Effect** An arc of electricity courses through the sea drake's blood. The triggering creature takes 1d6 electricity damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+17 ()\n__Damage__  2d8 + 9 piercing plus briny-wound"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+17 (agile, reach 10 feet)\n__Damage__  2d6 + 9 bludgeoning"

  - name: "Ball Lightning Breath"
    desc: "`pf2:2` (arcane,electricity) The sea drake spews a ball of electricity that strikes a primary target within 100 feet, dealing 7d6 electricity damage (DC 24 Reflex check save). The lightning then arcs to up to three secondary targets within 30 feet of the primary target, striking the closest available targets first. The secondary bolts each strike one secondary target and deal the same rolled damage value as the primary bolt (DC 22 Reflex check save).\n\nThe sea drake can't use Ball Lightning Breath again for 1d6 rounds."

  - name: "Briny Wound"
    desc: "  A sea drake's saliva carries a large quantity of salt, making its bite wounds even more painful. When a creature takes damage from a sea drake's jaws Strike, the creature must attempt a DC 24 Fortitude check save; the creature is then temporarily immune to briny wound for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature is Sickened 2 and [[Conditions/Slowed|Slowed 1]] as long as it's sickened."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The drake tries to capsize an adjacent aquatic vessel of its size or smaller. The drake must succeed at an Athletics check with a DC of 25 (reduced by 5 for each size smaller the vessel is than the drake) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The sea drake makes one jaws Strike and two tail Strikes in any order."

  - name: "Speed Surge"
    desc: "`pf2:1`  **Frequency** three times per day\n* * *\n\n**Effect** The sea drake Strides, Flies, or Swims twice."
 
```

```encounter-table
name: Sea Drake
creatures:
  - 1: Sea Drake
```



Long and slender, sea drakes have fins down the length of their backs and webbing between their talons, making them just as adapted for gliding through ocean waves as the skies above. More solitary than most drakes, they hunt and live alone. Although most sea drakes make their roosts high on ocean-facing cliffs, it isn't unheard of for them to dwell in underwater caves, living entirely aquatic lives.

* * *

Distant cousins to dragons, drakes menace and terrorize settlements.
