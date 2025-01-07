---
title: "Daemonic Skinner"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OjZOR51RCHx8XjCh" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Daemonic Skinner"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Daemonic Skinner"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[daemon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[human]]
trait_06: [[humanoid]]
trait_07: [[unholy]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Greater Darkvision"
languages: "Common, Daemonic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +40, Intimidation: +34, Religion: +34, Stealth: +34, Thievery: +32"
abilityMods: [10, 6, 9, 3, 6, 6]
speed: 30 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +39, __Ref__ +34, __Will__ +32"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450; __Immunities__  bleed,  void,  poison,  disease; __Weaknesses__ holy 20; __Resistances__ precision 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Orc Necksplitter|+3 Wounding Greater Striking Cleaver (Large)]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Bloody Chain Aura"
    desc: " (aura,divine) 20 feet. Chains of blood bind a bleeding creature to the Daemonic Skinner.\n\nCreatures in range that are taking [[Conditions/Persistent Damage|Persistent Bleed Damage]] can't move out of the aura.\n\nThe Skinner can have only one aura active at a time.\n\nShe can switch her active aura as an Interact action."

  - name: "Spell Choke"
    desc: "`pf2:r`  **Trigger** A creature taking [[Conditions/Persistent Damage|Persistent Bleed Damage]] within 30 feet of the Daemonic Skinner Casts a Spell with a verbal component or speaks\n* * *\n\n**Effect** The Skinner wills the triggering creature's blood to gush from their mouth and constrict their throat. The target's spell is disrupted.\n\nThe target must succeed at a DC 47 Fortitude check save or become [[Conditions/Sickened|Sickened 2]]."

  - name: "Transfusion Aura"
    desc: " (aura,divine,healing) 30 feet. Any time a creature in the aura takes [[Conditions/Persistent Damage|Persistent Bleed Damage]], the Daemonic Skinner regains the same number of Hit Points as the damage dealt.\n\nThe Skinner can have only one aura active at a time.\n\nShe can switch her active aura as an Interact action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cleaver"
    desc: "+38 (forceful, magical, reach 10 feet, sweep, unholy)\n__Damage__  4d8 + 20 slashing 2d6 spirit 1d6 bleed"

  - name: "**Melee** `pf2:1` Blood Chain"
    desc: "+36 (disarm, finesse, magical, reach 20 feet, trip, unholy)\n__Damage__  4d8 + 20 piercing plus grab 2d6 spirit plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __6th __ (1 slots) _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_, _[[Spells/Weapon Storm|Weapon Storm]]_; __5th __ (1 slots) _[[Spells/Translocate|Dimension Door]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Bloody Sneak Attack]]"
    desc: "  Any creature taking [[Conditions/Persistent Damage|Persistent Bleed Damage]] is [[Conditions/Off-Guard|Off-Guard]] against the Daemonic Skinner's attacks. When attacking an off-guard creature, the Skinner deals an additional 2d6 precision damage."

  - name: "Hook and Flay"
    desc: "`pf2:2`  **Requirements** The Daemonic Skinner has a creature grabbed with her blood chain or a creature is affected by her bloody chain aura\n* * *\n\n**Effect** The Skinner pulls the creature into the nearest open adjacent square and makes a cleaver Strike against the creature."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Daemonic Skinner
creatures:
  - 1: Daemonic Skinner
```




