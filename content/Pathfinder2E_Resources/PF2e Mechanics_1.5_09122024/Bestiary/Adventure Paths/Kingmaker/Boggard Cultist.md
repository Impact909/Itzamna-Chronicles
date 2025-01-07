---
title: "Boggard Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i9IcX2ubyre5lckw" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/boggard
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Boggard Cultist"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Boggard Cultist"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[boggard]]
trait_03: [[chaotic]]
trait_04: [[evil]]
trait_05: [[humanoid]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Boggard, Chthonian, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +16, Intimidation: +17, Medicine: +18, Nature: +15, Performance: +15, Religion: +17, Stealth: +17"
abilityMods: [4, 5, 4, 3, 6, 3]
speed: 20 feet,  swim 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +14, __Ref__ +17, __Will__ +18"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Blowgun|Blowgun]], [[Equipment/Whip|+1 Striking Whip]], [[Equipment/Hide Armor|Hide Armor]], 6x [[Equipment/Blowgun Darts|Blowgun Darts]], [[Equipment/Giant Wasp Venom|Giant Wasp Venom (On Darts)]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+16 (reach 10 feet)\n__Damage__ "

  - name: "**Melee** `pf2:1` Whip"
    desc: "+18 (disarm, finesse, magical, nonlethal, reach 10 feet, trip)\n__Damage__  2d6 + 8 slashing"

  - name: "**Ranged** `pf2:1` Blowgun"
    desc: "+17 (agile, nonlethal, range increment 20 feet, reload 1)\n__Damage__  1 piercing plus giant-wasp-venom"

  - name: "Primal Prepared Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Divine Wrath|Divine Wrath]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Vampiric Feast|Vampiric Touch]]_; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/See the Unseen|See Invisibility]]_, _[[Spells/Noise Blast|Sound Burst]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(4th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Gogunta's Croak"
    desc: "`pf2:1` (auditory,divine,emotion,fear,mental) The boggard cultist unleashes a terrifying croak. Any non-boggard within 30 feet must attempt a DC 25 Will check save.\n* * *\n\n**Critical Success** The creature is temporarily immune to Gogunta's Croak for 1 minute.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]]\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]] and is also [[Conditions/Fleeing|Fleeing]] during their next turn."

  - name: "Swamp Stride"
    desc: "  A boggard cultist ignores difficult terrain caused by swamp terrain features."

  - name: "Tongue Grab"
    desc: "  If the boggard cultist hits a creature with its tongue, that creature becomes [[Conditions/Grabbed|Grabbed]] by the boggard. Unlike with a normal Grab, the creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the boggard's tongue. A creature can sever the tongue by hitting AC 25 and dealing at least 10 slashing damage. Though this doesn't deal any damage to the boggard, it prevents it from using its tongue Strike until it regrows its tongue, which takes a week."
 
```

```encounter-table
name: Boggard Cultist
creatures:
  - 1: Boggard Cultist
```


Variant Boggard

Boggards are aggressive humanoid amphibians that thrive in swamps, marshes, and even some rain forests. Boggards hatch from eggs into tadpoles, fiercely competing for food and even consuming their siblings in that struggle. Over 3 years, the surviving boggards develops arms, legs, and lungs while learning the rudiments of hunting, crafts, and warfare-everything needed to survive in their might-makes-right society. At the top of most boggard hierarchies lords a hulking swampseer imbued with sinister divine magic.
