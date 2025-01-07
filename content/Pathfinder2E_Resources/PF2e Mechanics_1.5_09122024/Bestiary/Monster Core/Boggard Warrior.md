---
title: "Boggard Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kwM7DFupqzlNlGs6" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Boggard Warrior"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Boggard Warrior"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Boggard"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +5, Stealth: +6"
abilityMods: [4, 0, 4, -1, 2, 1]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +10, __Ref__ +5, __Will__ +8"
hp: 38
health:
  - name: ""
  - name: HP
    desc: "38"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Club|Club]], 3x [[Equipment/Javelin|Javelin]], [[Equipment/Studded Leather Armor|Studded Leather Armor]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Club"
    desc: "+10 ()\n__Damage__  1d6 + 6 bludgeoning"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+10 (reach 10 feet)\n__Damage__ "

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+6 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Club"
    desc: "+6 (thrown 10 ft.)\n__Damage__  1d6 + 6 bludgeoning"

  - name: "Swamp Passage"
    desc: "  A boggard warrior ignores difficult terrain caused by swamp terrain features."

  - name: "Terrifying Croak"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The boggard warrior unleashes a terrifying croak. Any non-boggard within 30 feet becomes [[Conditions/Frightened|Frightened 1]] unless they succeed at a DC 18 Will check save; those who critically succeed are temporarily immune for 1 minute."

  - name: "Tongue Grab"
    desc: "  If the boggard warrior hits a creature with their tongue, that creature becomes [[Conditions/Grabbed|Grabbed]] by the boggard. Unlike with a normal Grab, the creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the boggard's tongue. A creature can sever the tongue by hitting AC 15 and dealing at least 3 slashing damage. Though this doesn't deal any damage to the boggard, it prevents them from using their tongue Strike until they regrow their tongue, which takes a week."
 
```

```encounter-table
name: Boggard Warrior
creatures:
  - 1: Boggard Warrior
```



Boggard warriors exalt single combat and prefer to fight alone so that no one can contest their kills. They have been known to pursue enemies who flee combat with a single-mindedness that seems almost supernatural.

* * *

Boggards are aggressive humanoid amphibians who thrive in swamps, marshes, and even some rain forests. Boggards hatch from eggs into tadpoles, fiercely competing for food and even consuming their siblings in that struggle. Over 3 years, the surviving boggards develop arms, legs, and lungs while learning the rudiments of hunting, crafts, and warfare—everything needed to survive in their might-makes-right society. At the top of most boggard hierarchies lords a hulking swampseer imbued with sinister divine magic.
