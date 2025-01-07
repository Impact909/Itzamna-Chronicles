---
title: "Everburning Mammoth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lyzJpxhzTdQFBIZ2" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Everburning Mammoth"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Everburning Mammoth"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Hallit"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Stealth: +17"
abilityMods: [5, 5, 4, 1, 4, 0]
speed: 30 feet
sourcebook: "_Pathfinder #177: Burning Tundra_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +16, __Ref__ +17, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Spurred by Death"
    desc: "`pf2:r`  **Trigger** An ally within 30 feet reduces a creature to 0 HP\n* * *\n\n**Effect** The everburning mammoth uses Drink Blood on a creature that meets the ability's requirements."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (finesse)\n__Damage__  2d6 + 8 piercing plus paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile, finesse)\n__Damage__  2d6 + 6 slashing plus grab"

  - name: "Drink Blood"
    desc: "`pf2:1` (divine) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], [[Conditions/Unconscious|Unconscious]], or willing creature is within the everburning mammoth's reach\n* * *\n\n**Effect** The everburning mammoth tears into the creature with its jaws and gorges itself on the victim's blood. This requires an Athletics check check against the victim's Fortitude DC if the victim is grabbed and is automatic for any of the other conditions. The victim is [[Conditions/Drained|Drained 1]], and the everburning mammoth regains 15 HP, gaining any excess HP as temporary Hit Points. Drinking Blood from a creature that's already drained doesn't restore any HP to the everburning mammoth but increases the victim's drain value by 1."

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any nonliving creature hit by the everburning mammoth's jaws Strike must succeed at a DC 23 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."
 
```

```encounter-table
name: Everburning Mammoth
creatures:
  - 1: Everburning Mammoth
```




