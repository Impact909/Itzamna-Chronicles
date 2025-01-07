---
title: "Hamatula"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.scRQ6fMTdRRfQE91" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Hamatula"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Hamatula"
level: "Creature 11"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Greater Darkvision"
languages: "Diabolic, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Arcana: +18, Intimidation: +21, Religion: +20, Stealth: +23, Survival: +22"
abilityMods: [7, 6, 5, 1, 5, 4]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +20, __Will__ +20; +1 status to all saves vs. magic"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165; __Immunities__  fire; __Weaknesses__ holy 10; __Resistances__ physical 10 (except silver), poison 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  Barb only. A hamatula gains an extra reaction at the start of each of its turns that it can use only to make an Attack of Opportunity. It can't use more than one Attack of Opportunity triggered by the same action. In addition to the normal trigger, a hamatula can make an Attack of Opportunity against a creature that touches it or an adjacent creature that attempts a melee Strike against it.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Barb"
    desc: "+24 (magical, unholy)\n__Damage__  3d8 + 13 piercing plus bloodletting 1d6 spirit plus bloodletting"

  - name: "**Ranged** `pf2:1` Hurled Barb"
    desc: "+23 (magical, range increment 60 feet, unholy)\n__Damage__  2d8 + 13 piercing plus bloodletting 1d6 spirit plus bloodletting"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +21; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Rune Trap|Glyph of Warding (At will)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __3rd __  _[[Spells/Harm|Harm]]_, _[[Spells/Paralyze|Paralyze (x2)]]_\n__Cantrips__  __(6th)__ _[[Spells/Produce Flame|Produce Flame]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Bloodletting"
    desc: "  On a critical hit, the hamatula's barbs deal 3d6 bleed."

  - name: "Frightful Strike"
    desc: " (divine,emotion,fear,mental) **Trigger** The hamatula hits a creature with a barb Strike\n* * *\n\n**Effect** The creature struck must succeed at a DC 27 Will check save or become [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). Regardless of the result of its saving throw, the creature is then temporarily immune to Frightful Strike for 24 hours."

  - name: "Impaling Barb"
    desc: "`pf2:2`  The hamatula makes a barb Strike, then Strides up to half its Speed without triggering reactions. If the Strike hits, the hamatula impales the target with one of its barbs and snaps the barb free as it moves away from the target. This deals an additional 2d8 piercing damage to the target and pins it to an adjacent surface, rendering it [[Conditions/Immobilized|Immobilized]] ([[Actions/Escape|Escape]] DC 29)."

  - name: "Warden of Erebus"
    desc: "  A hamatula's [[Spells/Rune Trap|Rune Trap]] innate spell can contain any common spell from the Core Rulebook that meets the criteria in glyph of warding; the hamatula doesn't need to provide the spell."
 
```

```encounter-table
name: Hamatula
creatures:
  - 1: Hamatula
```



Hamatulas are forged in Erebus to protect infernal vaults from those foolish enough to try to rob the archdevil Mammon. In case the vicious spines protruding from their bodies and ability to teleport weren't deadly enough, they are also clever wielders of warding glyphs. They are effective conjured guardians, though they resent being pulled away from their duties in Hell. Unlike most fiends, hamatulas are formed from several souls that lack any features distinctive enough to merit another role.
