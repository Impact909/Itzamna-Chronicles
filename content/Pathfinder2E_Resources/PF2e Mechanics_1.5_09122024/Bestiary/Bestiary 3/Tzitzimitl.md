---
title: "Tzitzimitl"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1wMooFB6b4LlYA3u" 
tags:
  - pf2e/creature/type/electricity
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Tzitzimitl"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Tzitzimitl"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[electricity]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Truesight"
languages: "Aklo, Chthonian, Common, Empyrean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Arcana: +37, Athletics: +33, Nature: +37, Occultism: +37, Religion: +40"
abilityMods: [10, 8, 6, 5, 7, 8]
speed: 50 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +29, __Ref__ +32, __Will__ +35"
hp: 390
health:
  - name: ""
  - name: HP
    desc: "390, fast healing 15, void healing; __Immunities__  death effects,  disease,  electricity,  void,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ holy 15; __Resistances__ cold 15, physical 15 (except bludgeoning)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 15]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Light to Dark"
    desc: "`pf2:r` (divine,void) **Trigger** A creature uses an ability or spell with the vitality trait within 120 feet of the tzitzimitl\n* * *\n\n**Effect** The tzitzimitl inverts the energy used in the triggering ability or spell, causing it to lose the vitality trait and gain the void trait, and changing all instances of vitality energy or healing in the ability's description to void energy."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+34 (agile, magical, reach 20 feet)\n__Damage__  4d12 + 10 slashing plus drain-life 3d8 electricity plus drain-life"

  - name: "**Ranged** `pf2:1` Eye Beam"
    desc: "+34 (range 100 feet)\n__Damage__  4d12 electricity 10d6 force"

  - name: "Occult Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Darkness|Darkness (x3)]]_, _[[Spells/Teleport|Teleport]]_, _[[Spells/Wails of the Damned|Wail of the Banshee]]_; __7th __  _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Teleport|Teleport (x3)]]_; __5th __  _[[Spells/Abyssal Plague|Abyssal Plague]]_; __4th __  _[[Spells/Darkness|Darkness (x3)]]_, _[[Spells/Haste|Haste (x3)]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Create Undead_, _Imprisonment_"

  - name: "Drain Life"
    desc: "  When a tzitzimitl's claw Strike deals damages to a living creature, the tzitzimitl gains 20 temporary Hit Points, and the target must succeed at a DC 41 Fortitude check save or become [[Conditions/Drained|Drained 2]]. Further damage dealt by a tzitzimitl's Claw Strike increases the value of the drained condition by 2 on a failed save, to a maximum of drained 4."

  - name: "Eclipse"
    desc: "`pf2:2` (cold,occult) **Effect** The tzitzimitl casts [[Spells/Darkness|Darkness]] and drains the heat and warmth from the Darkness spell's area, and each creature within the spell's area must attempt a DC 41 Fortitude check save.\n* * *\n\n**Critical Success** The creature takes 4d8 cold damage.\n\n**Success** The creature takes 8d8 cold damage and is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The creature takes 16d8 cold damage and is [[Conditions/Slowed|Slowed 1]] for 1 minute.\n\n**Critical Failure** The creature takes 16d8 cold damage, is [[Conditions/Slowed|Slowed 2]] for 1 minute, and is [[Conditions/Doomed|Doomed 1]]."
 
```

```encounter-table
name: Tzitzimitl
creatures:
  - 1: Tzitzimitl
```



Due to their affinity for darkness and apocalyptic terror, tzitzimitls are widely feared as harbingers of death and destruction. A solar eclipse marks their arrivals, and they draw strange powers of darkness and electricity from these phenomena.

Some sages believe tzitzimitls to be instruments of the gods, called down to destroy worlds whose times have come, while others claim they're the undead remains of stranded exiles from a far-off civilization of spacefaring giants. The legends that include them are ancient and fragmented, but some tell of tzitzimitls being defeated by great heroes and sealed away-though these tales imply that the enormous undead now lie buried and waiting, soon to rampage again should their tombs be breached.
