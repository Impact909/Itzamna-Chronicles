---
title: "Shinigami"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.trCMF97WNQ46q32N" 
tags:
  - pf2e/creature/type/lawful
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Shinigami"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #196: The Summer That Never Was"
name: "Shinigami"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[lawful]]
trait_02: [[monitor]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Truesight"
languages: "Common, Diabolic, Draconic, Empyrean, Necril, Requian, Utopian; truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Arcana: +30, Diplomacy: +32, Intimidation: +34, Occultism: +30, Religion: +33, Society: +30, Stealth: +31, Boneyard Lore: +32"
abilityMods: [8, 6, 7, 5, 6, 9]
speed: 25 feet,  fly 30 feet
sourcebook: "_Pathfinder #196: The Summer That Never Was_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +29, __Will__ +31; +1 status to all saves vs. magic"
hp: 260
health:
  - name: ""
  - name: HP
    desc: "260, fast healing 40; __Immunities__  death effects,  disease,  void; __Weaknesses__ silver 15; __Resistances__ physical 15 (except silver), cold 15, poison 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Naginata|+2 Greater Striking Naginata]], [[Equipment/Sack|Pouch of Four Gems]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Naginata"
    desc: "+33 (deadly d8, magical, reach 15 feet, versatile p)\n__Damage__  3d8 + 16 slashing 1d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Seize Soul|Bind Soul (x3)]]_; __8th __  _[[Spells/Execute|Finger of Death]]_, _[[Spells/Scrying|Scrying]]_; __7th __  _[[Spells/Enervation|Enervation]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_\n__Constant__  __(9th)__ _[[Spells/Detect Alignment|Detect Alignment]]_, _[[Spells/Truesight|True Seeing]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The shinigami takes on the appearance of a specific Small or Medium humanoid creature. This doesn't change their statistics, other than to remove the reach trait from their Strikes. The shinigami's human shape is unique to the shinigami and can't be used to Impersonate a creature.\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Pouch of Four Gems"
    desc: "  Each shinigami carries a pouch containing four black sapphires for use with [[Spells/Seize Soul|Seize Soul]]. Each gem is capable of holding a soul of a maximum level equal to that of the shinigami. If the shinigami dies, the gems are destroyed as well, and any souls they contain are released harmlessly to travel to the Boneyard."

  - name: "Release Soul"
    desc: "`pf2:2`  **Requirements** One of the gems in the shinigami's pouch contains a soul from bind soul\n* * *\n\n**Effect** The shinigami crushes the gem, sending the soul to the Boneyard while releasing a wave of necromantic energy. All creatures within a 30-foot emanation take 18d6 damage (DC 38 Fortitude check save); the shinigami chooses whether this damage is vitality damage or void damage. A creature who takes damage from this effect and fails the saving throw is also [[Conditions/Sickened|Sickened 2]] and [[Conditions/Drained|Drained 1]] (or [[Conditions/Sickened|Sickened 4]] and [[Conditions/Drained|Drained 2]] on a critical failure)."

  - name: "Spirit Touch"
    desc: "  A shinigami's Strikes can affect incorporeal creatures with the effect of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune."
 
```

```encounter-table
name: Shinigami
creatures:
  - 1: Shinigami
```



Even immortals such as kami aren't immune to death. When a kami or equally powerful entity refuses the call of the Boneyard, a shinigami is summoned to bring these stubborn souls to heel. Exact and swift, shinigami are known to dispense the judgment of death efficiently and dispassionately.

## Guardians Of The Cycle

Shinigami are responsible for investigating and dealing with widespread phenomena that disrupt the natural flow of life. They might be tasked with solving the issue or be told to wait, observe, and provide minimal assistance. While most shinigami can retain their impartiality during such long vigils, some are far from emotionless and end up wavering toward mercy or cruelty.
