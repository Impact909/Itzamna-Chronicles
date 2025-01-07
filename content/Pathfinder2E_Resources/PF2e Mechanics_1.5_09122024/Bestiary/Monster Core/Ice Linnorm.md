---
title: "Ice Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EnY0MJAZYwSVblQQ" 
tags:
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/17
  - remaster
statblock: inline
name: "Ice Linnorm"
level: 17
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ice Linnorm"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[cold]]
trait_02: [[dragon]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +32"
abilityMods: [9, 5, 7, -3, 6, 7]
speed: 35 feet,  fly 100 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +32, __Ref__ +28, __Will__ +27; +1 status to all saves vs. magic"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330, regeneration 10 (deactivated by cold iron); __Immunities__  cold,  curse,  paralyzed,  sleep; __Weaknesses__ cold iron 15, fire 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Curse of Frost"
    desc: " (cold,curse,primal) When a creature slays the ice linnorm, it must succeed at a DC 40 Will check save or gain weakness to cold 15 with an unlimited duration.\n\n[[Bestiary Effects/Effect_ Curse of Frost|Effect: Curse of Frost]]"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 (magical, reach 25 feet)\n__Damage__  3d12 + 17 piercing plus ice-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 20 feet)\n__Damage__  3d8 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+34 (agile, magical, reach 25 feet)\n__Damage__  3d6 + 17 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 38, attack +30\n__Constant__  __(8th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_ __(7th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+18 bludgeoning, DC 38 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Ice Linnorm Venom"
    desc: " (cold,injury,poison) **Saving Throw** DC 38 Fortitude check\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 5d6 cold damage and [[Conditions/Drained|Drained 1]] (1 round);\n\n**Stage 2** 7d6 cold damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "Icemire Breath"
    desc: "`pf2:2` (cold,primal) The ice linnorm spews out a blast of freezing, viscous ooze in a 60-foot cone that deals 15d6 cold damage to creatures within the area (DC 38 Reflex check save).\n\nThe freezing ooze clings to those struck and hardens into thick sheets of ice. A creature that fails the saving throw is [[Conditions/Immobilized|Immobilized]] by the ice until it succeeds at a check to [[/act escape dc=34]] or it or an ally [[/act force-open dc=34]]{Forces Open} the ice (DC 34 for either case). At the start of its turn, a creature still immobilized by the ice takes 4d6 cold damage. Another creature can free a frozen target by dealing a total of 20 fire damage to the frozen target. Left unattended, the ice crumbles away in 1 minute on its own.\n\nCreatures with the fire trait can't be frozen in place by Icemire Breath. Flying creatures fall if frozen, and swimming creatures that are frozen rise toward the surface of the water at a speed of 60 feet per round.\n\nThe linnorm can't use Icemire Breath again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ice Linnorm
creatures:
  - 1: Ice Linnorm
```



The ice linnorm dwells amid glacial crevasses, atop wind-blasted mountain peaks, or within glittering caverns carved from the hearts of the mightiest of icebergs.

* * *

Immense, primeval dragons of the northern reaches of the world, linnorms hate those they deem to be lesser creatures and seek to inflict as much suffering as possible upon their unfortunate victims. While these serpentine monstrosities might not be the powerful winged dragons most imagine, they nonetheless possess incredible strength and deadly powers that often rival authentic dragon brutality.
