---
title: "Fafnheir"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MvD4lIq42WlovC9u" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/24
statblock: inline
name: "Fafnheir"
level: 24
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Fafnheir"
level: "Creature 24"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
modifier: 38
perception:
  - name: "Perception"
    desc: "+38; Darkvision, Scent (Imprecise) 120 Feet, Truesight"
languages: "Aklo, Common, Draconic, Fey, Skald"
skills:
  - name: "Skills"
    desc: "Acrobatics: +40, Arcana: +35, Athletics: +48, Intimidation: +45, Nature: +35, Stealth: +40, Survival: +40, First World Lore: +40, Saga Lands Lore: +35"
abilityMods: [12, 9, 12, 4, 9, 9]
speed: 50 feet,  burrow 25 feet,  fly 160 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 51
armorclass:
  - name: AC
    desc: "51; __Fort__ +42, __Ref__ +36, __Will__ +38; +1 status to all saves vs. magic"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500, regeneration 20 (deactivated by cold iron); __Immunities__  curse,  electricity,  fire,  paralyzed,  sleep; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Attack of Opportunity"
    desc: "  `pf2:r` Tail only."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Curse of the Woeful Wyrd"
    desc: " (curse,primal) When a creature slays Fafnheir, it becomes home to his soul, which slowly emerges from his killer's body. The creature must attempt a DC 52 Will check save or become [[Conditions/Doomed|Doomed 2]] ([[Conditions/Doomed|Doomed 1]] on a success, unaffected on a critical success). Unless the creature critically succeeded at the saving throw, each day the doomed value increases by 1. If the creature dies while suffering the curse of the woeful wyrd, its corpse explodes in a 60-foot burst with the effect of Blasting Breath. Fafnheir is immediately returned to life in the nearest available space to the corpse with full Hit Points and no conditions. Even an indirect slaying usually still allows Fafnheir to curse the soul of his slayer through the metaphysical link between them."

  - name: "Enormous"
    desc: "  Fafnheir takes up a space of 6 squares by 6 squares (30 feet by 30 feet) and is 60 feet long."

  - name: "Extra Reactions"
    desc: "  Fafnheir gains 2 reactions at the start of each of his turns."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 45 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Spit Boiling Blood"
    desc: "`pf2:r`  **Trigger** A creature within 60 feet damages Fafnheir\n* * *\n\n**Effect** Fafnheir spits blood at the creature. It must immediately attempt a Fortitude save against boiling blood."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+44 (magical, reach 25 feet)\n__Damage__  4d12 + 26 piercing plus boiling-blood"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+44 (agile, magical, reach 25 feet)\n__Damage__  4d10 + 22 slashing"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+44 (deadly d12, magical, reach 25 feet)\n__Damage__  4d12 + 26 bludgeoning"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+44 (agile, magical, reach 30 feet)\n__Damage__  4d10 + 22 bludgeoning plus improved-grab"

  - name: "Innate Primal Spells"
    desc: "DC 45, attack +37; __10th __  _[[Spells/Interplanar Teleport|Plane Shift (At Will, Only to the First World or the Material Plane)]]_, _[[Spells/Spell Turning|Spell Turning (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Blasting Breath"
    desc: "`pf2:2` (electricity,fire,primal) Fafnheir exhales a cataclysmic firestorm laced with lightning and hurricane-strength winds, dealing 20d6 fire damage in a 90-foot cone (DC 48 Reflex check save). Additionally, Fafnheir deals 10d6 additional electricity damage to one creature within the area of Blasting Breath of Fafnheir's choice, determined by the same basic Reflex save. Creatures in the area must also attempt a DC 48 Fortitude check save to resist the powerful winds and deafening thunderclaps of the breath. Creatures that fail experience the effects of [[Spells/Gust of Wind|Gust of Wind]], affecting Large or smaller creatures as normal. Finally, creatures that fail their Fortitude save become [[Conditions/Deafened|Deafened]] for 1 minute (permanently deafened on a critical failure)."

  - name: "Boiling Blood"
    desc: " (fire,poison) **Saving Throw** DC 48 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 6d8 fire damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 6d10 fire damage and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 6d12 fire damage and [[Conditions/Drained|Drained 3]] (1 round)"

  - name: "Furious Frenzy"
    desc: "`pf2:2`  Fafnheir makes two claw Strikes and one Strike with his jaws, horns, or tail, in any order."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Fafnheir
creatures:
  - 1: Fafnheir
```



Fafnheir is the fabled Father of Linnorms. He's larger than all other linnorms on Golarion, with a length of 60 feet and a weight upwards of 10 tons. Fafnheir is a clever and powerful creature, worthy of the fear of all people in the Lands of the Linnorm Kings.
