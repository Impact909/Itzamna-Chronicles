---
title: "Majungasaurus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i2CsZkOLBCQQ0t2j" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/dinosaur
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Majungasaurus"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Majungasaurus"
level: "Creature 6"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[dinosaur]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +16, Intimidation: +14, Stealth: +16"
abilityMods: [6, 5, 4, -4, 2, 4]
speed: 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +14, __Ref__ +17, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120"
abilities_top:
  - name: ""

  - name: "Frightened Prey"
    desc: "  [[Conditions/Frightened|Frightened]] creatures are [[Conditions/Off-Guard|Off-Guard]] to a majungasaurus."

  - name: "Startling Roar"
    desc: "  When the majungasaurus rolls initiative using Stealth, it can attempt to [[Actions/Demoralize|Demoralize]] each creature within 30 feet as a free action. Regardless of the effect, each creature is then temporarily immune for 1 hour."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+16 (reach 15 feet)\n__Damage__  2d8 + 6 piercing plus grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+16 (agile)\n__Damage__  2d6 + 6 bludgeoning"

  - name: "Crack Bones"
    desc: "`pf2:1`  **Requirements** The majungasaurus has a creature [[Conditions/Grabbed|Grabbed]] in its jaws\n* * *\n\n**Effect** The majungasaurus deals that creature 3d8 bludgeoning damage (DC 24 Fortitude check save). A creature that fails this save is [[Conditions/Clumsy|Clumsy 1]] until it recovers to full Hit Points."
 
```

```encounter-table
name: Majungasaurus
creatures:
  - 1: Majungasaurus
```



The majungasaurus prowls in a crouched posture, carrying its bulk so low to the ground it is eye-to-eye with its prey. Unlike most carnivorous dinosaurs, the majungasaurus is primarily an ambush predator, patiently lying in wait for quarry to come within reach before bursting from cover with a signature cry to attack.
