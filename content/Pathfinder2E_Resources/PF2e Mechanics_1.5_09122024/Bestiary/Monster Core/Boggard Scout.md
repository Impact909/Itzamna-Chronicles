---
title: "Boggard Scout"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.goOYKne9v697fGU6" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Boggard Scout"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Boggard Scout"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[humanoid]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Boggard, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +8, Stealth: +7"
abilityMods: [3, 2, 4, -1, 2, 0]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +5, __Will__ +7"
hp: 24
health:
  - name: ""
  - name: HP
    desc: "24"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Morningstar|Morningstar]], [[Equipment/Sling|Sling]], [[Equipment/Leather Armor|Leather Armor]], 10x [[Equipment/Sling Bullets|Sling Bullets]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Morningstar"
    desc: "+8 (versatile p)\n__Damage__  1d6 + 3 bludgeoning"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+8 (reach 10 feet)\n__Damage__ "

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+7 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d6 + 1 bludgeoning"

  - name: "Swamp Passage"
    desc: "  A boggard scout ignores difficult terrain caused by swamp terrain features."

  - name: "Terrifying Croak"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The boggard scout unleashes a terrifying croak. Any non-boggard within 30 feet becomes [[Conditions/Frightened|Frightened 1]] unless they succeed at a DC 17 Will check save; those who critically succeed are temporarily immune for 1 minute."

  - name: "Tongue Grab"
    desc: "  If the boggard scout hits a creature with their tongue, that creature becomes [[Conditions/Grabbed|Grabbed]] by the boggard. Unlike with a normal Grab, the creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the boggard's tongue. A creature can sever the tongue by hitting AC 13 and dealing at least 2 slashing damage. Though this doesn't deal any damage to the boggard, it prevents them from using their tongue Strike until they regrow their tongue, which takes a week."
 
```

```encounter-table
name: Boggard Scout
creatures:
  - 1: Boggard Scout
```



Often tasked with patrolling the borders of their lands, boggard scouts learn to speak another language (typically Common) to deal with trespassers.

* * *

Boggards are aggressive humanoid amphibians who thrive in swamps, marshes, and even some rain forests. Boggards hatch from eggs into tadpoles, fiercely competing for food and even consuming their siblings in that struggle. Over 3 years, the surviving boggards develop arms, legs, and lungs while learning the rudiments of hunting, crafts, and warfare—everything needed to survive in their might-makes-right society. At the top of most boggard hierarchies lords a hulking swampseer imbued with sinister divine magic.
