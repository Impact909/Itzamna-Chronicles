---
title: "Jaggaki"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4eXGHJqmjxsmmXL2" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Jaggaki"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Jaggaki"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Jotun, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Arcana: +27, Athletics: +25, Intimidation: +23, Stealth: +21"
abilityMods: [6, 2, 4, 5, 3, 4]
speed: 35 feet
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +21, __Ref__ +21, __Will__ +22; +1 status to all saves vs. vitality"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Resistances__ cold 20, physical 15 (except magical bludgeoning)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Staff of the Dead (Greater)|+1 Striking Staff of Necromancy (Greater)]]"
abilities_mid:
  - name: ""
  - name: "Catch Rock"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

  - name: "[[Creature Family Ability Glossary/(Lich) Rejuvenation|Rejuvenation]]"
    desc: " (arcane) When a lich is destroyed, its soul immediately transfers to its _[[Equipment/Lich Soul Cage|Soul Cage]]_. A lich can be permanently destroyed only if its _soul cage_ is found and destroyed."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Staff"
    desc: "+26 (two-hand d8)\n__Damage__  2d4 + 12 bludgeoning"

  - name: "**Melee** `pf2:1` Hand"
    desc: "+25 (magical)\n__Damage__  4d8 void plus lich-paralyzing-touch"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+25 (brutal, range increment 120 feet)\n__Damage__  2d6 + 12 bludgeoning"

  - name: "Arcane Prepared Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Petrify|Flesh to Stone]]_; __5th __  _[[Spells/Black Tentacles|Black Tentacles]]_, _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Cone of Cold|Cone of Cold]]_; __4th __  _[[Spells/Fly|Fly]]_, _[[Spells/Phantasmal Killer|Phantasmal Killer]]_; __3rd __  _[[Spells/Blindness|Blindness]]_, _[[Spells/Fireball|Fireball]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Slow|Slow]]_; __2nd __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Mirror Image|Mirror Image]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_; __1st __  _[[Spells/Grim Tendrils|Grim Tendrils]]_, _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Enfeeble|Ray of Enfeeblement]]_\n__Cantrips__  __(7th)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Ray of Frost|Ray of Frost]]_, _[[Spells/Read Aura|Read Aura]]_, _[[Spells/Shield|Shield]]_"

  - name: "Bones of Stone"
    desc: "`pf2:1` (arcane,earth) **Requirements** The target is standing on or adjacent to a stone surface.\n\n**Frequency** once per round\n* * *\n\n**Effect** Jaggaki calls upon unquiet spirits within the land, causing a giant skeletal arm made of jagged stone to reach out of a stone surface adjacent to a creature within 60 feet. Jaggaki makes a hand Strike against the target via this stone arm rather than using his own hand. If the Strike hits, it deals 4d6 bludgeoning damage."

  - name: "[[Creature Family Ability Glossary/(Lich) Drain Soul Cage|Drain Soul Cage]]"
    desc: "  **Frequency** once per day\n* * *\n\n**Effect** Jaggaki taps into his _[[Equipment/Lich Soul Cage|Soul Cage's]]_ power to cast any arcane spell up to the highest level he can cast, even if the spell being cast is not one of the lich's prepared spells.\n\nJaggaki's _soul cage_ doesn't need to be present for him to use this ability."

  - name: "[[Creature Family Ability Glossary/(Lich) Paralyzing Touch|Paralyzing Touch]]"
    desc: " (arcane,curse,incapacitation) A creature damaged by the Jaggaki's hand Strike must succeed at a DC 29 Fortitude check save.\n\nThe creature becomes [[Conditions/Paralyzed|Paralyzed]] for 1 round on a failure. On a critical failure, the creature is paralyzed permanently, falls [[Conditions/Prone|Prone]], and seems dead. A DC 25 Medicine check check reveals the victim is alive."

  - name: "Steady Spellcasting"
    desc: "  If another creature's reaction would disrupt Jaggaki's spellcasting action, Jaggaki attempts a DC 15 Flat check check. If he succeeds, his action isn't disrupted."
 
```

```encounter-table
name: Jaggaki
creatures:
  - 1: Jaggaki
```




