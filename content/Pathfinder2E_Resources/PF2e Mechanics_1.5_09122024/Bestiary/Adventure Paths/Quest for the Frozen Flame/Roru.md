---
title: "Roru"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.R2nyWJKnpBDR9tSn" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Roru"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Roru"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Chthonian, Draconic, Empyrean; speak with animals, telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +17, Intimidation: +15, Nature: +14, Survival: +16"
abilityMods: [6, 4, 2, 0, 3, 2]
speed: 40 feet
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +17, __Will__ +12"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Weaknesses__ cold iron 5, holy 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Disobedience Vulnerability"
    desc: "  The first time each round an attempt to Command an Animal fails within 60 feet of a roru, the roru takes 4d6 mental damage (10d6 mental if the roru failed the attempt)."

  - name: "Predatory Aura"
    desc: " (aura) 30 feet. An animal or beast entering or starting its turn in the emanation must succeed at a DC 25 Will check save or become [[Conditions/Frightened|Frightened 1]] (frightened 2 on a critical failure). Frightened animals within the emanation can't attack the roru. A creature that succeeds at a saving throw against predatory aura is immune for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+18 (magical, unholy)\n__Damage__  2d10 + 8 piercing 1d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+18 (agile, magical, unholy)\n__Damage__  2d6 + 8 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __6th __ (1 slots) _[[Spells/Dominate|Dominate (Animals Only)]]_; __5th __ (1 slots) _[[Spells/Translocate|Dimension Door]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(2nd)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Incite Ferocity"
    desc: "`pf2:1` (divine,mental) The roru focuses its corruption on an animal or beast it can see within 30 feet. The creature must succeed at a DC 25 Will check save or become [[Conditions/Confused|Confused]] for 1d4 rounds. The confused creature can't attack the roru. A creature that succeeds at its saving throw is temporarily immune to Incite Ferocity for 24 hours."

  - name: "Wear Pelt"
    desc: "`pf2:2` (divine,manipulate) The roru dons the pelt of an adjacent dead animal, transforming into its lookalike. The roru becomes the same size and gains the same Speeds as the target animal. The roru loses its claw and jaws unarmed Strikes and gains the types of melee Strikes of the animal whose pelt it wears. The Strike deals damage equal to the roru's jaws Strike or, if the Strike has the agile trait, the roru's claw Strike. Either way, the damage type changes to match the new unarmed attack. While a roru wears a pelt, half of physical damage dealt to the roru is instead dealt to the pelt. A pelt has Hardness 5 and 25 HP. When a pelt reaches 0 HP, the roru is immediately expelled from the pelt and it is destroyed."
 
```

```encounter-table
name: Roru
creatures:
  - 1: Roru
```



Rorus, sometimes called hunter demons, are brutal fiends that arise from the souls of mortals who mutilated animal corpses. As demons, these individuals don animal pelts, then infiltrate packs or herds to corrupt entire swaths of animals, turning their victims bloodthirsty and feral.
