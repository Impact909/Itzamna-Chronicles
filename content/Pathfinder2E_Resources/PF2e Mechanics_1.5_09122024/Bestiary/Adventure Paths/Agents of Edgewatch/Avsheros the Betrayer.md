---
title: "Avsheros the Betrayer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.plltHNtkPCyz414Z" 
tags:
  - pf2e/creature/type/angel
  - pf2e/creature/type/celestial
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/23
statblock: inline
name: "Avsheros the Betrayer"
level: 23
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Avsheros the Betrayer"
level: "Creature 23"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[angel]]
trait_02: [[celestial]]
trait_03: [[chaotic]]
trait_04: [[evil]]
trait_05: [[unholy]]
modifier: 41
perception:
  - name: "Perception"
    desc: "+41; Darkvision, Truesight"
languages: "Diabolic, Draconic, Empyrean; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +44, Intimidation: +43, Religion: +41"
abilityMods: [11, 7, 9, 6, 8, 10]
speed: 35 feet,  fly 60 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 50
armorclass:
  - name: AC
    desc: "50; __Fort__ +40, __Ref__ +36, __Will__ +41; +1 status to all saves vs. magic"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400, regeneration 20 (deactivated by unholy); __Weaknesses__ holy 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+3 Major Striking Greatsword (Large)]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated by Unholy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Hateful Gaze"
    desc: " (aura,divine,visual) 60 feet. When a creature ends its turn in the aura, it must attempt a DC 45 Fortitude check save. If the creature fails, it is [[Conditions/Drained|Drained 1]] and [[Conditions/Sickened|Sickened 1]] ([[Conditions/Drained|Drained 2]] and [[Conditions/Sickened|Sickened 2]] on a critical failure).\n\nAvsheros can deactivate or activate this aura using a single action, which has the concentrate trait.\n\nNo matter the result of the save, a creature can't be affected by Avsheros's hateful gaze again for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Unholy Greatsword"
    desc: "+42 (magical, reach 10 feet, unholy, versatile p)\n__Damage__  4d12 + 21 slashing"

  - name: "**Ranged** `pf2:1` Radiant Ray"
    desc: "+40 (magical, range increment 60 feet, unholy)\n__Damage__  6d6 + 15 fire 2d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 47, attack +39; __10th __  _[[Spells/Weapon of Judgment|Weapon of Judgment]]_; __9th __  _[[Spells/Earthquake|Earthquake]]_, _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Prismatic Shield|Prismatic Shield]]_, _[[Spells/Prismatic Sphere|Prismatic Sphere]]_; __8th __  _[[Spells/Power Word Stun|Power Word Stun]]_, _[[Spells/Spiritual Epidemic|Spiritual Epidemic]]_; __7th __  _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Heal|Heal]]_; __4th __  _[[Spells/Discern Lies|Discern Lies (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_\n__Cantrips__  __(10th)__ _[[Spells/Light|Light]]_\n__Constant__  __(5th)__ _[[Spells/Detect Alignment|Detect Alignment]]_, _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Blasphemous Arms"
    desc: "  Any weapon gains the effects of an _[[Equipment/Unholy|Unholy]]_ property rune while Avsheros wields it."

  - name: "Wail of the Betrayed"
    desc: "`pf2:2` (auditory,fear,mental) Avsheros lets out an agonized wail that invokes grief and a feeling of betrayal in those who hear it.\n\nAll creatures within 120 feet must succeed at a DC 47 Will check save or become [[Conditions/Frightened|Frightened 2]]. A creature frightened in this way can't willingly accept aid of any kind from an ally until the frightened condition is removed.\n\nOn a successful save, the creature is immune to Avsheros's Wail of the Betrayed for 24 hours."
 
```

```encounter-table
name: Avsheros the Betrayer
creatures:
  - 1: Avsheros the Betrayer
```




