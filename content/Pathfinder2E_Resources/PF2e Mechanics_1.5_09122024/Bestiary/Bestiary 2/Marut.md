---
title: "Marut"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uM9NSutcZVtjlvb6" 
tags:
  - pf2e/creature/type/aeon
  - pf2e/creature/type/inevitable
  - pf2e/creature/type/lawful
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Marut"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Marut"
level: "Creature 15"

alignment: ""
size: "Large"
trait_01: [[aeon]]
trait_02: [[inevitable]]
trait_03: [[lawful]]
trait_04: [[monitor]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Truesight"
languages: "Diabolic, Empyrean, Utopian; truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Diplomacy: +27, Intimidation: +29, Religion: +26, Survival: +28, Axis Lore: +22"
abilityMods: [8, 4, 6, 1, 5, 6]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +25, __Will__ +26; +2 status to all saves vs. magic"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230, regeneration 15 (deactivated by chaotic); __Immunities__  death effects,  disease,  emotion,  poison,  unconscious"
abilities_top:
  - name: ""

  - name: "Truespeech"
    desc: "  A marut can speak with and understand any creature with a language."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Chaotic)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+30 (magical, reach 10 feet)\n__Damage__  3d8 + 11 bludgeoning plus fists-of-thunder-and-lightning 1d6 spirit plus fists-of-thunder-and-lightning"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +27; __8th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Earthquake|Earthquake]]_, _[[Spells/Harm|Harm]]_; __7th __  _[[Spells/Fear|Fear]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __  _[[Spells/Command|Command]]_, _[[Spells/Locate|Locate]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_\n__Constant__  __(8th)__ _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Geas_"

  - name: "Final End"
    desc: "  The marut is anathema to beings that unnaturally extend their existence, including undead. Its fists bypass such creatures' resistances to damage and apply the creatures' highest weakness to damage. If a marut kills a creature that rejuvenates, like a lich or ghost, it always knows that the creature isn't fully defeated."

  - name: "Fists of Thunder and Lightning"
    desc: " (divine,incapacitation) Each time the marut makes a fist Strike, it chooses either lightning or thunder.\n\n*   If it chooses lightning, the attack deals an additional 2d12 electricity damage and the target must succeed at a DC 33 Fortitude check save or be [[Conditions/Blinded|Blinded]] for 1 minute.\n*   If it chooses thunder, the attack deals an additional 3d8 sonic damage and the target must succeed at a DC 36 Fortitude check save or be [[Conditions/Deafened|Deafened]] for 1 minute."
 
```

```encounter-table
name: Marut
creatures:
  - 1: Marut
```



A marut is tasked with hunting mortals who cheat death by artificially extending their lifespans. This includes those who seek undeath, such as liches and vampires, but also includes those who use powerful magic to cling to their youth, use divination to discover and avoid an appointed death, or call too often on the power of resurrection. Once the marut has selected its target, the inevitable pursues its quarry without surcease or deviation until either it or the target is dead.

Maruts seem to be carved from stone and clad in golden armor, yet they move with the deliberate grace of a creature made of flesh and bone. A marut never rushes, but its thunderous footfalls are relentless as it pursues its target. Though able to speak any language, the marut is taciturn even among inevitables.
