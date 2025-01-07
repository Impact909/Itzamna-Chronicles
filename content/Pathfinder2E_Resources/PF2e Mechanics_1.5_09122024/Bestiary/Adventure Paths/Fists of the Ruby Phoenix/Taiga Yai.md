---
title: "Taiga Yai"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XeHSGWONhMiwRGff" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oni
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Taiga Yai"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #167: Ready? Fight!"
name: "Taiga Yai"
level: "Creature 15"

alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[giant]]
trait_04: [[humanoid]]
trait_05: [[oni]]
trait_06: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Greater Darkvision"
languages: "Common, Jotun; speak with animals"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Arcana: +26, Athletics: +27, Deception: +27, Intimidation: +27, Nature: +30, Survival: +32"
abilityMods: [6, 8, 8, 5, 7, 6]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #167: Ready? Fight!_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +29, __Will__ +30; +1 status to all saves vs. magic"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270, regeneration 15 (deactivated by fire)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortbow|+2 Greater Striking Shortbow]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Botanic Interruption"
    desc: " (primal) **Trigger** The taiga yai is standing in natural foliage or undergrowth and is targeted by a melee attack\n* * *\n\n**Effect** The taiga yai infuses their power within the plants around them, causing the plants to shoot up and create a protective barrier. The taiga yai gains a +2 circumstance bonus to AC against the triggering attack roll. If the attack misses, the attacker must attempt a DC 33 Reflex check save. On a failed save, the attacker is [[Conditions/Immobilized|Immobilized]] for 1 round as the plants grab hold of them; on a critical failure, the attacker is also knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+27 (agile, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 12 bludgeoning 2d6 acid"

  - name: "**Ranged** `pf2:1` Acid Missile"
    desc: "+29 (acid, magical, range increment 60 feet, reload 0, unholy)\n__Damage__  3d8 + 10 acid"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+31 (deadly 2d10, range increment 60 feet, unholy)\n__Damage__  3d6 piercing"

  - name: "Innate Primal Spells"
    desc: "DC 34, attack +26; __8th __  _[[Spells/Earthquake|Earthquake (x2)]]_, _[[Spells/Summon Animal|Summon Animal]]_; __7th __  _[[Spells/Shifting Sand|Shifting Sand (x2)]]_; __6th __  _[[Spells/Tangling Creepers|Tangling Creepers (x2)]]_; __4th __  _[[Spells/Darkness|Darkness]]_; __2nd __  _[[Spells/Entangling Flora|Entangle (At Will)]]_, _[[Spells/Invisibility|Invisibility (at will, self only)]]_\n__Constant__  __(8th)__ _[[Spells/Speak with Animals|Speak with Animals]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The taiga yai takes on the appearance of a [[Bestiary 2/Taiga Giant|Taiga Giant]]. This doesn't change their Speed or Strike attack and damage.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Return to Nature"
    desc: "`pf2:1` (earth,manipulate) The taiga yai commands underground plant roots to drag a creature within 60 feet into the earth. The target must succeed at a DC 35 Fortitude check save or be [[Conditions/Immobilized|Immobilized]] for 1d4 rounds. After this time, the creature is buried; it is [[Conditions/Grabbed|Grabbed]], begins to suffocate, and takes 4d6 bludgeoning damage each round they remain buried. To [[Actions/Escape|Escape]] either while immobilized or grabbed, the creature must succeed at a DC 35 Escape check or an adjacent ally must succeed at a DC 33 Athletics check check to pull them out."
 
```

```encounter-table
name: Taiga Yai
creatures:
  - 1: Taiga Yai
```



Wearing the visage of taiga giants, taiga yais generally travel in a solitary fashion, always yearning for new experiences and destinations. They are zealous in their love of nature in its purest form and gleefully destroy any established civilizations that they encounter before continuing onwards.
