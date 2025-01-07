---
title: "Daemonic Infector"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.0utwLRwsVCc1HS7E" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/22
statblock: inline
name: "Daemonic Infector"
level: 22
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Daemonic Infector"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[unholy]]
modifier: 40
perception:
  - name: "Perception"
    desc: "+40; Greater Darkvision, Truesight"
languages: "Common, Daemonic, Diabolic, Osiriani, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +39, Crafting: +39, Deception: +40, Diplomacy: +40, Intimidation: +40, Religion: +42, Society: +36, Stealth: +37, Thievery: +35, Norgorber Lore: +39"
abilityMods: [6, 9, 10, 7, 10, 8]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +40, __Ref__ +39, __Will__ +40"
hp: 475
health:
  - name: ""
  - name: HP
    desc: "475; __Immunities__  death effects,  disease,  poison; __Weaknesses__ fire 20, holy 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Combustible"
    desc: "  The first time each round that the Daemonic Infector takes fire damage, his fumes combust, dealing 30 fire damage to all other creatures within the area of his toxic fumes aura."

  - name: "Toxic Fumes"
    desc: " (aura,inhaled,poison) 10 feet. A creature that enters or begins its turn within the aura must attempt a DC 44 Fortitude check save.\n\nOn a failed save, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, it's also [[Conditions/Clumsy|Clumsy 1]] for 1 minute. In addition, creatures within the aura attempting a flat check to remove [[Conditions/Persistent Damage|Persistent Poison Damage]] must roll twice and take the lower result."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+36 (agile, finesse, magical, unholy)\n__Damage__  4d8 + 14 slashing 1d6 spirit"

  - name: "Divine Prepared Spells"
    desc: "DC 46, attack +38; __10th __  _[[Spells/Miracle|Miracle]]_; __9th __  _[[Spells/Telepathic Demand|Telepathic Demand]]_; __8th __  _[[Spells/Spiritual Epidemic|Spiritual Epidemic]]_; __7th __  _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Energy Aegis|Energy Aegis]]_, _[[Spells/Regenerate|Regenerate]]_; __6th __  _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Spirit Blast|Spirit Blast]]_, _[[Spells/Truesight|True Seeing]]_; __5th __  _[[Spells/Abyssal Plague|Abyssal Plague]]_, _[[Spells/Sending|Sending]]_; __4th __  _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Discern Lies|Discern Lies]]_, _[[Spells/Divine Wrath|Divine Wrath]]_; __3rd __  _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Heroism|Heroism]]_, _[[Spells/Locate|Locate]]_, _[[Spells/Cleanse Affliction|Neutralize Poison]]_; __2nd __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Silence|Silence]]_, _[[Spells/Spiritual Weapon|Spiritual Weapon]]_; __1st __  _[[Spells/Command|Command]]_, _[[Spells/Harm|Harm]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Cleanse Cuisine|Purify Food and Drink]]_, _[[Spells/Sanctuary|Sanctuary]]_\n__Cantrips__  __(10th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Message|Message]]_, _[[Spells/Shield|Shield]]_"

  - name: "Divine Innate Spells"
    desc: "DC 46, attack +38\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_ __(4th)__ _[[Spells/Fly|Fly]]_"

  - name: "Cleric Domain Spells"
    desc: "3 Focus Points, DC 46, attack +38; __10th __  _[[Spells/Death's Call|Death's Call]]_, _[[Spells/Eradicate Undeath|Eradicate Undeath]]_"

  - name: "Breathe Death"
    desc: "`pf2:2` (divine,poison) The Daemonic Infector exhales a 30-foot line of concentrated fumes.\n\nEach creature in the area takes 12d10 poison damage (DC 44 Fortitude check save; on a critical failure the creature is also [[Conditions/Drained|Drained 1]]).\n\nThe Infector can't Breathe Death again for 1d4 rounds."

  - name: "Infector"
    desc: "`pf2:2` (concentrate,divine) The Daemonic targets a creature within 30 feet that's currently subject to a poison affliction. The poison affliction progresses to the next stage."

  - name: "Steady Spellcasting"
    desc: "  If a reaction would disrupt the Daemonic Infector's spellcasting action, he attempts a DC 15 Flat check check. On a success, the action isn't disrupted."
 
```

```encounter-table
name: Daemonic Infector
creatures:
  - 1: Daemonic Infector
```




