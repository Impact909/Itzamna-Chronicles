---
title: "Eberark"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bsaO010T3NIt8WTx" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Eberark"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Eberark"
level: "Creature 10"

alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[fire]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common, Pyric"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +21, Intimidation: +21, Stealth: +18, Survival: +19"
abilityMods: [7, 4, 5, 2, 3, 3]
speed: 40 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +19, __Will__ +16"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Immunities__  fire"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (magical, reach 15 feet)\n__Damage__  2d10 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, fire, magical, reach 15 feet)\n__Damage__  2d6 + 11 slashing 1d4 fire"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+21 (agile, range increment 30 feet)\n__Damage__ "

  - name: "Arrogant Taunts"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The eberark utters crude insults and growls threateningly. Each creature within 30 feet must attempt a DC 27 Will check save.\n\nThe creature is then temporarily immune for 10 minutes.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Paralyzed|Paralyzed]] for 1 round.\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]] and paralyzed for 1d4 rounds."

  - name: "Incendiary Spit"
    desc: "  A creature hit by the eberark's spit becomes coated in a slippery, flammable oil.\n\nThe creature must succeed at a DC 27 Reflex check save or become [[Conditions/Clumsy|Clumsy 2]] for as long as they are coated in incendiary spit.\n\nCreatures affected by incendiary spit that take fire damage catch fire, taking 3d6 persistent fire damage. Once this persistent fire damage ends, the spit has burned away."

  - name: "Trail of Flame"
    desc: "`pf2:2` (fire) The eberark Strides twice, leaving a trail of magical fire behind it as it moves. Squares the eberark moves through catch fire, creating a 5-foot-tall wall of flame that burns for 1 round. The wall of flame conceals creatures and objects on the other side of it.\n\nAny creature that enters or starts its turn in the wall of flame takes 6d6 fire damage (DC 27 Reflex check save)."
 
```

```encounter-table
name: Eberark
creatures:
  - 1: Eberark
```




