---
title: "Tor Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Xz3LyUac3VKrYxg0" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/fire
  - pf2eMonster
  - pf2e/creature/level/21
  - remaster
statblock: inline
name: "Tor Linnorm"
level: 21
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tor Linnorm"
level: "Creature 21"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[dragon]]
trait_02: [[fire]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +40, Stealth: +37"
abilityMods: [11, 8, 9, -1, 8, 9]
speed: 35 feet,  climb 35 feet,  fly 100 feet,  swim 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 47
armorclass:
  - name: AC
    desc: "47; __Fort__ +38, __Ref__ +35, __Will__ +33; +1 status to all saves vs. magic"
hp: 440
health:
  - name: ""
  - name: HP
    desc: "440, regeneration 20 (deactivated by cold iron); __Immunities__  curse,  fire,  paralyzed,  sleep; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Curse of Boiling Blood"
    desc: " (curse,fire,primal) When a creature slays the linnorm, it must succeed at a DC 48 Will check save or gain weakness to fire 20 and [[Conditions/Slowed|Slowed 1]] from the agonizing pain it now endures at all times, with an unlimited duration.\n\nAs long as a character continues to suffer this curse, its slowed condition can never be reduced below slowed 1.\n\n[[Bestiary Effects/Effect_ Curse of Boiling Blood|Effect: Curse of Boiling Blood]]"

  - name: "Lava Affinity"
    desc: "  A tor linnorm can breathe and swim freely while submerged in lava and magma."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+40 (magical, reach 30 feet)\n__Damage__  4d12 + 19 piercing plus tor-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+40 (agile, magical, reach 30 feet)\n__Damage__  4d8 + 19 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+40 (agile, magical, reach 30 feet)\n__Damage__  4d6 + 19 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 44, attack +36\n__Constant__  __(9th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_ __(8th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d6+21 bludgeoning, DC 46 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Pyroclastic Breath"
    desc: "`pf2:2` (fire,primal) The tor linnorm expels a 60-foot cone of flame and ash dealing 20d6 fire damage to creatures within the area (DC 46 Reflex check save).\n\nThe linnorm can't use Pyroclastic Breath again for 1d4 rounds.\n\nAt the start of the tor linnorm's next turn, the area of the Pyroclastic Breath is covered in thick, scorching smoke that burns both the lungs and eyes, dealing an additional 10d6 fire damage to all creatures in the area (DC 46 Reflex check save). A creature that spends an entire round in the smoke with open eyes must succeed at a DC 44 Fortitude check save or be [[Conditions/Blinded|Blinded]] for 1 minute.\n\nThe smoke dissipates after 1 minute; in strong winds, the smoke dissipates in 5 rounds, and in more powerful winds, it may clear even more quickly."

  - name: "Slashing Claws"
    desc: "`pf2:1`  The tor linnorm makes four Strikes with their claws, each against a different target. These attacks count toward the tor linnorm's multiple attack penalty, but the multiple attack penalty doesn't increase until after the tor linnorm makes all their attacks."

  - name: "Tor Linnorm Venom"
    desc: " (fire,injury,poison) **Saving Throw** DC 44 Fortitude check;\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 8d6 fire damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 12d6 fire damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tor Linnorm
creatures:
  - 1: Tor Linnorm
```



Tor linnorms dwell in the tallest volcanic mountains, either within naturally formed caverns or molten craters. A tor linnorm's temper can be as hot and destructive as the magma the creature resembles.

* * *

Immense, primeval dragons of the northern reaches of the world, linnorms hate those they deem to be lesser creatures and seek to inflict as much suffering as possible upon their unfortunate victims. While these serpentine monstrosities might not be the powerful winged dragons most imagine, they nonetheless possess incredible strength and deadly powers that often rival more notorious dragons' brutality.
