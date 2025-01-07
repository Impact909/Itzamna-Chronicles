---
title: "Shanchek"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vuMPmbpMWvq066kS" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Shanchek"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Shanchek"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Thoughtsense (Imprecise) 60 Feet"
languages: "Draconic, Sakvroth; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Arcana: +27, Deception: +29, Diplomacy: +27, Intimidation: +29, Occultism: +31, Society: +27, Xulgath Lore: +31"
abilityMods: [4, 6, 4, 8, 5, 6]
speed: 25 feet,  fly 35 feet
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +23, __Ref__ +26, __Will__ +30"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280; __Resistances__ mental 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff of the Magi|Staff of the Magi]], [[Equipment/Spear|+2 Striking Spear]], [[Equipment/Leather Armor|+2 Resilient Leather Armor]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Thoughtsense|Thoughtsense (Imprecise) 60 feet]]"
    desc: "  Thoughtsense allows a monster to sense all non-mindless creatures at the listed range."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Psychogenic Secretions"
    desc: " (aura,mental) 30 feet. A creature that enters the emanation must attempt a DC 36 Will check save.\n\nOn a failure, the creature is [[Conditions/Stupefied|Stupefied 1]] for 1 minute ([[Conditions/Stupefied|Stupefied 2]] and also [[Conditions/Paralyzed|Paralyzed]] for 1 round on a critical failure).\n\nA creature that succeeds at its save is temporarily immune to psychogenic secretions for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 ()\n__Damage__  3d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile, finesse)\n__Damage__  3d4 + 10 slashing"

  - name: "**Melee** `pf2:1` Staff"
    desc: "+30 (magical, two-hand d8)\n__Damage__  4d4 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Spear"
    desc: "+30 (magical)\n__Damage__  2d6 + 10 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+30 (magical, thrown 20 ft.)\n__Damage__  2d6 + 10 piercing"

  - name: "Occult Spontaneous Spells"
    desc: "DC 36, attack +28; __7th __ (3 slots) _[[Spells/Phantasmal Killer|Phantasmal Killer]]_, _[[Spells/Visions of Danger|Visions of Danger]]_, _[[Spells/Warp Mind|Warp Mind]]_; __6th __ (3 slots) _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Scrying|Scrying]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __ (3 slots) _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Synaptic Pulse|Synaptic Pulse]]_; __4th __ (3 slots) _[[Spells/Invisibility|Invisibility]]_, _[[Spells/Rewrite Memory|Modify Memory]]_, _[[Spells/Suggestion|Suggestion]]_\n__Cantrips__  __(7th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +28; __8th __  _[[Spells/Phantom Pain|Phantom Pain]]_; __5th __  _[[Spells/Telekinetic Haul|Telekinetic Haul (At Will)]]_; __2nd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_\n__Constant__  __(8th)__ _[[Spells/Fly|Fly]]_"

  - name: "Rituals"
    desc: "_Inveigle_"

  - name: "Consume Knowledge"
    desc: "`pf2:2` (mental,occult) The thoughtmaw invades the mind of a creature within 100 feet and attempts to swallow its capacity for higher thought. The creature must attempt a DC 36 Will check save.\n\nUsing Consume Knowledge immediately ends any of the ability's previous effects on a different creature.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature is slowed 1 and can take no actions other than basic actions for 1 minute.\n\n**Critical Failure** As failure, and the thoughtmaw is [[Conditions/Quickened|Quickened 1]] for 1 minute. It can use this extra action to Stride, Strike, or Cast a Spell if the target had prepared spells or a spell repertoire."
 
```

```encounter-table
name: Shanchek
creatures:
  - 1: Shanchek
```


Female xulgath thoughtmaw

Xulgath thoughtmaws are inheritors of the xulgaths' ancient psychic legacy. They eagerly and liberally use their ability to extract knowledge from their foes to quicken their own prodigious intellects.
