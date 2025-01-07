---
title: "Magma Dragon (Ancient, Spellcaster)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BCGB9DLf7BjYlhAi" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Magma Dragon (Ancient, Spellcaster)"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Magma Dragon (Ancient, Spellcaster)"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[elemental]]
trait_04: [[fire]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Petran, Pyric, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +36, Deception: +28, Intimidation: +34, Nature: +28, Stealth: +28, Survival: +29"
abilityMods: [8, 4, 6, 4, 5, 6]
speed: 50 feet,  fly 200 feet,  swim 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +34, __Ref__ +30, __Will__ +31; +1 status to all saves vs. magic"
hp: 390
health:
  - name: ""
  - name: HP
    desc: "390; __Immunities__  fire,  paralyzed,  sleep; __Weaknesses__ cold 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 37 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Wing Deflection"
    desc: "`pf2:r`  **Trigger** The dragon is targeted with an attack\n* * *\n\n**Effect** The dragon raises a wing, gaining a +2 circumstance bonus to AC against the triggering attack. If the dragon is Flying, they descend 10 feet after the attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (magical, reach 20 feet)\n__Damage__  3d10 + 16 piercing 4d6 fire"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+36 (agile, magical, reach 15 feet)\n__Damage__  3d10 + 16 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+34 (magical, reach 25 feet)\n__Damage__  3d12 + 16 bludgeoning"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+34 (magical, reach 20 feet)\n__Damage__  3d10 + 16 piercing"

  - name: "Primal Prepared Spells"
    desc: "DC 42, attack +34; __8th __  _[[Spells/Earthquake|Earthquake]]_, _[[Spells/Desiccate|Horrid Wilting]]_, _[[Spells/Power Word Stun|Power Word Stun]]_; __7th __  _[[Spells/Fiery Body|Fiery Body]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Volcanic Eruption|Volcanic Eruption]]_; __6th __  _[[Spells/Fire Seeds|Fire Seeds]]_, _[[Spells/Petrify|Flesh to Stone]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Elemental Form|Elemental Form]]_, _[[Spells/Flame Strike|Flame Strike]]_; __4th __  _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Mountain Resilience|Stoneskin]]_, _[[Spells/Wall of Fire|Wall of Fire]]_; __3rd __  _[[Spells/Haste|Haste]]_, _[[Spells/Slow|Slow]]_, _[[Spells/Stinking Cloud|Stinking Cloud]]_; __2nd __  _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Mist|Obscuring Mist]]_, _[[Spells/Sound Body|Restore Senses]]_; __1st __  _[[Spells/Air Bubble|Air Bubble]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Vanishing Tracks|Pass Without Trace]]_\n__Cantrips__  __(8th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Prestidigitation|Prestidigitation]]_, _[[Spells/Produce Flame|Produce Flame]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __8th __  _[[Spells/Breathe Fire|Burning Hands (At Will)]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Wall of Fire|Wall of Fire (At Will)]]_\n__Cantrips__  __(8th)__ _[[Spells/Produce Flame|Produce Flame]]_\n__Constant__  __(4th)__ _[[Spells/Fire Shield|Fire Shield]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (fire,primal) The dragon breathes a blast of magma that deals 10d6 fire damage and 5d12 bludgeoning damage in a 60-foot cone (DC 40 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Magma Swim"
    desc: "  A magma dragon's swim Speed functions only when the dragon is Swimming through magma or molten lava."

  - name: "Magma Tomb"
    desc: "`pf2:2`  Once per day, the dragon can spit a molten boulder at a target within 120 feet. This deals 12d6 fire damage and 5d12 bludgeoning damage, with a DC 42 Reflex check save. If the creature fails its save, it's encased in magma that instantly cools and has Hardness 10, HP 40, and BT 20. The encased creature can't breathe and is [[Conditions/Restrained|Restrained]] (Escape DC 42)."

  - name: "Volcanic Purge"
    desc: "`pf2:1`  If the next action the dragon uses is Breath Weapon, the magma clings to those it damages. Each creature that fails its save against the Breath Weapon takes 5d6 persistent fire damage, and as long as it has this persistent fire damage, it also takes a -10-foot status penalty to its Speeds."
 
```

```encounter-table
name: Magma Dragon (Ancient, Spellcaster)
creatures:
  - 1: Magma Dragon (Ancient, Spellcaster)
```



Magma dragons have a reputation among other dragons for being unpredictable and brash. Their temperament and tendency for violent outbursts ensure that the typical magma dragon lives a solitary life, with hatchlings often bickering or fighting to establish dominance among themselves before they leave the nest. A magma dragon always has a reason for their outbursts and can always justify their sudden turns in mood, yet they rarely feel the need to do so.

Magma dragons build lairs within volcanically active mountains or deep underground amid vast lakes of bubbling magma. As with all true dragons, magma dragons keep hoards of treasure, but the nature of their searing lairs limits the type of valuables they collect to metals, gems, and items capable of resisting the heat of a volcano's core.
