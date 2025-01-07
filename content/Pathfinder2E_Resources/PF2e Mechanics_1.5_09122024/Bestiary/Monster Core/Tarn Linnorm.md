---
title: "Tarn Linnorm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ruO77U3HSuwiLgAw" 
tags:
  - pf2e/creature/type/acid
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Tarn Linnorm"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Tarn Linnorm"
level: "Creature 20"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[acid]]
trait_02: [[amphibious]]
trait_03: [[dragon]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Aklo, Draconic, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +38, Stealth: +34"
abilityMods: [10, 6, 8, -1, 7, 8]
speed: 35 feet,  fly 100 feet,  swim 80 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 46
armorclass:
  - name: AC
    desc: "46 all-around vision; __Fort__ +36, __Ref__ +32, __Will__ +31; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400, regeneration 15 (deactivated by cold iron); __Immunities__  acid,  curse,  paralyzed,  sleep; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Curse of Death"
    desc: " (curse,death,primal) When a creature slays the tarn linnorm, it must succeed at a DC 46 Will check save or it can no longer recover Hit Points via any means, such as healing spells, the Medicine skill, or natural healing from rest. This has an unlimited duration."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 30 feet)\n__Damage__  4d12 + 18 piercing plus tarn-linnorm-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 30 feet)\n__Damage__  4d8 + 18 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+38 (agile, magical, reach 30 feet)\n__Damage__  4d6 + 18 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 42, attack +34\n__Constant__  __(9th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_ __(8th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d6+18 bludgeoning, DC 44 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Corrosive Breath"
    desc: "`pf2:2` (acid,poison,primal) The tarn linnorm can expel either a 120-foot line or a 60-foot cone of acid, dealing 20d6 acid damage to creatures within the area (DC 44 Reflex check save).\n\nThe linnorm can't use Corrosive Breath or Double Breath again for 1d4 rounds.\n\nThe acid creates toxic fumes. At the beginning of the linnorm's next turn, those who failed the breath weapon's Reflex save must succeed at a DC 42 Fortitude check or gain [[Conditions/Sickened|Sickened 4]] from the poisonous fumes."

  - name: "Double Bite"
    desc: "`pf2:1`  The tarn linnorm Strides and then makes a jaws Strike with each of their heads, each against a different target. Both attacks count toward the tarn linnorm's multiple attack penalty, but the multiple attack penalty doesn't increase until after the tarn linnorm makes all of these attacks."

  - name: "Double Breath"
    desc: "`pf2:3`  The tarn linnorm uses Corrosive Breath twice. A creature attempts only one save and can take damage only once.\n\nThe linnorm can't use Corrosive Breath or Double Breath again for 2d4 rounds."

  - name: "Tarn Linnorm Venom"
    desc: " (acid,injury,poison) **Saving Throw** DC 44 Fortitude check\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 7d6 acid damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 11d6 acid damage and [[Conditions/Drained|Drained 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tarn Linnorm
creatures:
  - 1: Tarn Linnorm
```



Although more powerful linnorms exist, the multi-headed tarn linnorm can wreak an awe-inspiring amount of devastation.

* * *

Immense, primeval dragons of the northern reaches of the world, linnorms hate those they deem to be lesser creatures and seek to inflict as much suffering as possible upon their unfortunate victims. While these serpentine monstrosities might not be the powerful winged dragons most imagine, they nonetheless possess incredible strength and deadly powers that often rival more notorious dragons' brutality.
