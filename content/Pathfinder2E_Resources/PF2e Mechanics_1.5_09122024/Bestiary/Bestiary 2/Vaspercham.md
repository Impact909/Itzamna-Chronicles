---
title: "Vaspercham"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fkZDuabeuDocIj3O" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Vaspercham"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Vaspercham"
level: "Creature 17"

alignment: ""
size: "huge"
trait_01: [[aberration]]
trait_02: [[aquatic]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, See the Unseen"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Arcana: +33, Athletics: +33, Deception: +31, Intimidation: +29, Sea Lore: +33"
abilityMods: [8, 4, 6, 8, 5, 6]
speed: 20 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +31, __Ref__ +25, __Will__ +32; +1 status to all saves vs. magic"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335; __Weaknesses__ fire 15; __Resistances__ cold 10, electricity 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Magic-Warping Aura"
    desc: " (arcane,aura) 30 feet. A vaspercham's shell distorts nearby magic. Any creature in the aura who Casts a Spell must attempt a DC 37 Will check save.\n* * *\n\n**Critical Success** The spell is unaffected and the caster is temporarily immune to the magic-warping aura for 1 minute.\n\n**Success** The spell is unaffected, but if the spell allows a saving throw, the vaspercham gains a +1 circumstance bonus to save against it.\n\n**Failure** If the spell has a target and there are one or more viable targets within its range, the spell's target changes, determined randomly by the GM. If there is no other possible target within range or the spell has no target, the spell is disrupted.\n\n**Critical Failure** The caster instead Casts another Spell, choosing randomly from their spell repertoire, prepared spells, or available focus spells (as appropriate) and selecting any targets at random."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+33 (agile, magical, reach 20 feet)\n__Damage__  3d10 + 16 bludgeoning plus hallucinatory-brine"

  - name: "**Ranged** `pf2:1` Water Blast"
    desc: "+33 (brutal, magical, range increment 100 feet, water)\n__Damage__  2d8 + 16 bludgeoning plus hallucinatory-brine"

  - name: "Arcane Innate Spells"
    desc: "DC 41, attack +31; __9th __  _[[Spells/Cone of Cold|Cone of Cold]]_, _[[Spells/Spell Immunity|Spell Immunity]]_; __8th __  _[[Spells/Lightning Bolt|Lightning Bolt]]_; __7th __  _[[Spells/Regenerate|Regenerate]]_; __6th __  _[[Spells/Spellwrack|Spellwrack (x3)]]_; __5th __  _[[Spells/Control Water|Control Water]]_\n__Constant__  __(7th)__ _[[Spells/See the Unseen|See Invisibility]]_"

  - name: "Hallucinatory Brine"
    desc: " (arcane,illusion,mental) A creature hit by the vaspercham's Strikes or Mindwarping Tide must attempt a DC 38 Fortitude check save. On a failure, the creature is overwhelmed with phantasmal visions, becoming [[Conditions/Confused|Confused]] for 1 round (1 minute on a critical failure)."

  - name: "Mindwarping Tide"
    desc: "`pf2:1` (concentrate) The vaspercham releases an effusion of noxious water from its shell. Creatures within a 15-foot emanation must save against the vaspercham's hallucinatory brine."

  - name: "Whipping Tentacles"
    desc: "`pf2:2`  The vaspercham makes four tentacle Strikes, each against a different target. These attacks count toward the vaspercham's multiple attack penalty, but the multiple attack penalty doesn't increase until after the vaspercham makes all of their attacks."
 
```

```encounter-table
name: Vaspercham
creatures:
  - 1: Vaspercham
```



The darkly intelligent vaspercham, an aquatic horror who delights in violence and destruction, lurks in the shallows near shorelines. Once a vaspercham settles on a new home, they stubbornly stay there, regardless of any communities dwelling nearby. A vaspercham's physical might and magic-warping abilities make them incredibly hard to dislodge once entrenched, and many seaside communities have relocated after a vaspercham came calling. The monster responds only to strength, so one must best a vaspercham in combat to gain their begrudging cooperation. But once the creature recovers their strength, they inevitably betray any temporary alliance.
