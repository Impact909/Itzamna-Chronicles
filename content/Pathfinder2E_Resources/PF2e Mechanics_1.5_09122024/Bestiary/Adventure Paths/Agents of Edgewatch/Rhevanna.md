---
title: "Rhevanna"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kQ6SO7pxgmbGVjxI" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/22
statblock: inline
name: "Rhevanna"
level: 22
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Rhevanna"
level: "Creature 22"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 42
perception:
  - name: "Perception"
    desc: "+42; Greater Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +36, Arcana: +38, Athletics: +42, Deception: +43, Intimidation: +37, Religion: +38, Stealth: +36, Survival: +40"
abilityMods: [10, 8, 6, 6, 8, 11]
speed: 40 feet,  fly 80 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +33, __Ref__ +39, __Will__ +36; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  death effects; __Weaknesses__ holy 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+3 Greater Striking Spiked Chain]], 4x [[Equipment/Sapphire|Black Sapphire]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Plunder Life"
    desc: " (aura,divine) 60 feet. When a healing effect restores Hit Points to a non-fiend creature in the aura, the amount of Hit Points restored is halved. The rhevanna gains temporary Hit Points equal to the amount of Hit Points restored.\n\nThe rhevanna loses any remaining temporary Hit Points after 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+43 (disarm, magical, reach 10 feet, trip, unholy)\n__Damage__  3d8 + 18 slashing 3d6 spirit"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+40 (magical, unholy)\n__Damage__  4d6 + 18 slashing 3d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 45, attack +37; __10th __  _[[Spells/Dominate|Dominate]]_; __9th __  _[[Spells/Seize Soul|Bind Soul (At Will)]]_, _[[Spells/Planar Tether|Dimensional Anchor (At Will)]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Possession|Possession]]_; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (At Will) (Self Only)]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Scrying|Scrying]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(5th)__ _[[Spells/Detect Alignment|Detect Alignment (Good Only)]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Detaining Strike"
    desc: "  **Frequency** once per round\n\n**Trigger** The rhevanna hits a creature with a weapon Strike\n* * *\n\n**Effect** The rhevanna casts an innate [[Spells/Planar Tether|Planar Tether]] spell on the creature."

  - name: "Lifedrinker"
    desc: "`pf2:r` (divine,healing) **Trigger** The rhevanna kills a living creature of at least 16th level\n* * *\n\n**Effect** The rhevanna drinks the triggering creature's life force and regains 40 healing Hit Points. If the triggering creature is a celestial, the rhevanna instead regains 80 healing Hit Points."

  - name: "Malefic Binding"
    desc: "  The rhevanna can target celestials with their [[Spells/Seize Soul|Seize Soul]] ability, and a gem containing a celestial bound by a rhevanna has Hardness 40.\n\nIf the rhevanna destroys a gem in which they placed a celestial, the celestial is destroyed forever."
 
```

```encounter-table
name: Rhevanna
creatures:
  - 1: Rhevanna
```




