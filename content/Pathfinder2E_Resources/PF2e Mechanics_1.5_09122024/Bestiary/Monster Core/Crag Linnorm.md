---
title: "Crag Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3duNjaHRkvNBMrn1" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Crag Linnorm"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Crag Linnorm"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[fire]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +28"
abilityMods: [8, 4, 6, -3, 4, 5]
speed: 35 feet,  fly 100 feet,  swim 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +28, __Ref__ +24, __Will__ +22; +1 status to all saves vs. magic"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, regeneration 10 (deactivated by cold iron); __Immunities__  curse,  fire,  paralyzed,  sleep; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Curse of Fire"
    desc: " (curse,fire,primal) When a creature slays the crag linnorm, it must succeed at a DC 35 Will check save or gain weakness to fire 15 with an unlimited duration.\n\n[[Bestiary Effects/Effect_ Curse of Fire|Effect: Curse of Fire]]"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (magical, reach 20 feet)\n__Damage__  3d12 + 14 piercing plus crag-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+30 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 14 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+30 (agile, magical, reach 20 feet)\n__Damage__  3d6 + 14 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 33, attack +25\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+14 bludgeoning, DC 34 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crag Linnorm Venom"
    desc: " (fire,injury,poison) **Saving Throw** DC 34 Fortitude check;\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 4d6 fire damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 6d6 fire damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "Magma Breath"
    desc: "`pf2:2` (fire,primal) The crag linnorm breathes out a stream of magma in a 120-foot line that deals 12d6 fire damage to creatures within the area (DC 34 Reflex check save). Any creature that fails its save also takes 4d6 persistent fire damage.\n\nThe linnorm can't use Magma Breath again for 1d4 rounds.\n\nThe magma remains until the start of the linnorm's next turn. If the linnorm was on the ground, the magma remains as a burning line on the ground directly under the line of the Magma Breath; if the linnorm was airborne, the magma rains down in a sheet 60 feet high. Any creature that moves across or through the magma takes 6d6 fire damage (DC 34 Reflex check save).\n\nAt the start of the linnorm's next turn, the magma cools to a thin layer of brittle stone, or the magma rain finishes falling and turns to harmless pebbles. The cooled magma quickly degrades to powder and sand over the course of several hours."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Crag Linnorm
creatures:
  - 1: Crag Linnorm
```



Despite being among the weakest linnorms, the crag linnorm is a devastating predator, capable of quickly cooking their foes with their magma breath.

* * *

Immense, primeval dragons of the northern reaches of the world, linnorms hate those they deem to be lesser creatures and seek to inflict as much suffering as possible upon their unfortunate victims. While these serpentine monstrosities might not be the powerful winged dragons most imagine, they nonetheless possess incredible strength and deadly powers that often rival more notorious dragons' brutality.
