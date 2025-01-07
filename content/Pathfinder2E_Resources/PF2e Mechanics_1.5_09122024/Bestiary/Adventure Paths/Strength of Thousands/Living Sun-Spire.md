---
title: "Living Sun-Spire"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LSYa9BqYFNNJ1W9y" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Living Sun-Spire"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Living Sun-Spire"
level: "Creature 13"

alignment: ""
size: "grg"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [9, 2, 8, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +29, __Ref__ +19, __Will__ +17"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Hardness__ 14; __Immunities__  fire,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Construct Armor (Hardness 14)"
    desc: "  Like normal objects, the Living Sun-Spire has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness.\n\nOnce the statue is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 32."

  - name: "Steal the Sun"
    desc: "`pf2:r` (divine) **Trigger** A creature within 30 feet of the sun-spire begins to Cast a Spell that has the fire or light trait\n* * *\n\n**Effect** The sun-spire attempts to redirect the energy from the triggering effect into its sunlight stores. The sun-spire attempts to counteract the triggering spell with a +22 counteract bonus. If it successfully counteracts the spell, the sun-spire's sunlight stores are empowered. While empowered, the sun-spire deals an additional 2d8 fire damage with all of its attacks and abilities. The sun-spire remains empowered until the end of its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm"
    desc: "+28 (magical, reach 15 feet)\n__Damage__  3d12 + 11 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Spear"
    desc: "+28 (magical, reach 20 feet)\n__Damage__  3d12 + 11 piercing"

  - name: "**Ranged** `pf2:1` Sunfire Beam"
    desc: "+28 (fire, magical, range increment 100 feet)\n__Damage__  3d8 + 11 fire"

  - name: "Beam of the Seven Suns"
    desc: "`pf2:2` (divine,fire) The sun-spire collects solar energy and uses the energy to create a deadly beam of fire. It fires the beam in a 120-foot line, dealing 11d8 fire damage to all creatures in the line (DC 33 Reflex check save). The concentrated beam ignites everything in its path, including the air, creating a wall of burning flame along the line that continues to burn until the end of the sun-spire's next turn. This wall has the effects of a 5th-rank [[Spells/Wall of Fire|Wall of Fire]] spell, dealing 5d6 fire damage to any creature that crosses the wall or occupies the wall's area at the start of its turn. The sun-spire can't use the Beam of the Seven Suns again for 1d4 rounds, although rounds it's not in sunlight don't count toward this number."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, arm, DC 33 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Living Sun-Spire
creatures:
  - 1: Living Sun-Spire
```




