---
title: "Ulressia The Blessed"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xn9g7eiOG4j9bJwv" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/evil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Ulressia The Blessed"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Ulressia The Blessed"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[evil]]
trait_04: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Diplomacy: +35, Intimidation: +37, Religion: +33"
abilityMods: [10, 6, 7, 6, 6, 8]
speed: 40 feet,  fly 75 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +34, __Ref__ +33, __Will__ +31; +1 status to all saves vs. magic"
hp: 355
health:
  - name: ""
  - name: HP
    desc: "355; __Weaknesses__ holy 15; __Resistances__ energy 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|+3 Greater Striking Warhammer]], [[Equipment/Dagger|+1 Vorpal Dagger]]"
  - name: "Crystal Sense (Imprecise) 30 feet"
    desc: "  Ulressia automatically detects crystals or crystalline items within 30 feet."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Aura of Angry Crystals"
    desc: " (aura,divine,visual) 60 feet. Any creature that ends its turn in the aura while in possession of any crystals, gemstones, or other precious stones must attempt a DC 39 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected and is immune to the aura for 1 hour.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature's crystals reverberate with Ulressia's vengeful aura, sharpening at every corner and digging, as if powerfully magnetized, into the creature's flesh.\n\nThe creature takes 4d6 piercing damage, plus 5 void damage for every 2,000 gp the crystals are cumulatively worth (maximum 40 damage).\n\nThe creature can't discard the crystals until they leave the aura or roll a successful save against it.\n\n**Critical Failure** As failure, but 8d6 piercing damage, plus 10 void damage for every 2,000 gp of the crystals' value (maximum 80 damage).\n* * *\n\nUlressia can deactivate or activate this aura using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+38 (magical, shove)\n__Damage__  3d8 + 20 bludgeoning"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+34 (agile, finesse, magical, thrown 10 ft., versatile s)\n__Damage__  1d4 + 20 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 39, attack +33; __9th __ (2 slots) _[[Spells/Nature's Enmity|Nature's Enmity]]_, _[[Spells/Shattering Gem|Shattering Gem]]_; __8th __ (2 slots) _[[Spells/Shatter|Shatter (x2)]]_; __7th __ (6 slots) _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Unfettered Pack|Unfettered Pack]]_, _[[Spells/Wall of Ice|Wall of Ice]]_; __4th __ (2 slots) _[[Spells/Discern Lies|Discern Lies (At Will)]]_, _[[Spells/One with Stone|Meld into Stone]]_; __2nd __ (1 slots) _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_\n__Cantrips__  __(7th)__ _[[Spells/Light|Light]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Crystallize Blood"
    desc: "`pf2:2` (divine) Ulressia channels her warped powers over crystals through her blade and into a creature's body, partially crystallizing its blood.\n\nUlressia makes a melee dagger Strike. On a hit, the creature takes damage as normal and must also roll a DC 41 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Drained|Drained 1]].\n\n**Failure** The creature is [[Conditions/Drained|Drained 1]], plus [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Critical Failure** The creature is [[Conditions/Drained|Drained 2]], plus [[Conditions/Slowed|Slowed 1]] for 1d4 rounds."

  - name: "Stunning Strike"
    desc: "`pf2:1`  **Requirements** Ulressia hit a foe earlier this turn with a weapon Strike\n* * *\n\n**Effect** Ulressia makes a weapon Strike against the foe. On a success, the foe must succeed at a DC 41 Fortitude check save or become [[Conditions/Stunned|Stunned 1]]. On a critical failure, the foe is [[Conditions/Stunned|Stunned 2]] instead."
 
```

```encounter-table
name: Ulressia The Blessed
creatures:
  - 1: Ulressia The Blessed
```




