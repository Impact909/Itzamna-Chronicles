---
title: "Boggard Swampseer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a2TDSmjKtL7Zh4LK" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Boggard Swampseer"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Boggard Swampseer"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Boggard, Chthonian, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Intimidation: +8, Medicine: +9, Nature: +11, Performance: +8, Religion: +9"
abilityMods: [3, 0, 2, 0, 4, 3]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +7, __Will__ +11"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff|Staff]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+10 (two-hand d8)\n__Damage__  1d4 + 6 bludgeoning"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+10 (reach 10 feet)\n__Damage__ "

  - name: "Primal Prepared Spells"
    desc: "DC 21, attack +11; __2nd __  _[[Spells/Acid Grip|Acid Grip]]_, _[[Spells/Mist|Mist]]_; __1st __  _[[Spells/Fear|Fear]]_, _[[Spells/Jump|Jump]]_, _[[Spells/Runic Weapon|Runic Weapon]]_\n__Cantrips__  __(2nd)__ _[[Spells/Caustic Blast|Caustic Blast]]_, _[[Spells/Frostbite|Frostbite]]_, _[[Spells/Tangle Vine|Tangle Vine]]_"

  - name: "Destructive Croak"
    desc: "`pf2:2` (sonic) The swampseer utters a powerful croak that deals 4d6 sonic damage to any non-boggard within a 15-foot emanation (DC 19 Fortitude check save); any creature with the frightened condition takes additional sonic damage equal to twice the value of its frightened condition.\n\nThe boggard can't use Destructive Croak again for 1d4 rounds."

  - name: "Drowning Drone"
    desc: "`pf2:r` (auditory,mental) **Trigger** The boggard swampseer or one of their allies within 60 feet attempts a saving throw against an auditory or sonic effect\n* * *\n\n**Effect** The swampseer releases a croak that drowns out other sounds. They roll a Performance check check. They and boggard allies in the area can use the higher result between the swampseer's Performance check and their saves to resolve the effects against the auditory or sonic effect."

  - name: "Swamp Passage"
    desc: "  A boggard swampseer ignores difficult terrain caused by swamp terrain features."

  - name: "Terrifying Croak"
    desc: "`pf2:1` (auditory,emotion,fear,mental) The boggard swampseer unleashes a terrifying croak. Any non-boggard within 30 feet becomes [[Conditions/Frightened|Frightened 1]] unless they succeed at a DC 19 Will check save; those who critically succeed are temporarily immune for 1 minute."

  - name: "Tongue Grab"
    desc: "  If the boggard swampseer hits a creature with their tongue, that creature becomes [[Conditions/Grabbed|Grabbed]] by the boggard. Unlike with a normal Grab, the creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the boggard's tongue. A creature can sever the tongue by hitting AC 15 and dealing at least 4 slashing damage. Though this doesn't deal any damage to the boggard, it prevents them from using their tongue Strike until they regrow their tongue, which takes a week."
 
```

```encounter-table
name: Boggard Swampseer
creatures:
  - 1: Boggard Swampseer
```



The boggard swampseer has been gifted with magic through their worship of the demon lord Gogunta, and they use their power to rule a boggard village, keeping the rest of the village in line and planning raids on nearby communities.

* * *

Boggards are aggressive humanoid amphibians who thrive in swamps, marshes, and even some rain forests. Boggards hatch from eggs into tadpoles, fiercely competing for food and even consuming their siblings in that struggle. Over 3 years, the surviving boggards develop arms, legs, and lungs while learning the rudiments of hunting, crafts, and warfare—everything needed to survive in their might-makes-right society. At the top of most boggard hierarchies lords a hulking swampseer imbued with sinister divine magic.
