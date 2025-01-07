---
title: "Muurfeli"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MdFqAK4cgB7tScWc" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/genie
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Muurfeli"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Muurfeli"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[chaotic]]
trait_03: [[elemental]]
trait_04: [[genie]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "Sakvroth, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Arcana: +27, Athletics: +31, Deception: +28, Stealth: +31"
abilityMods: [7, 9, 5, 5, 3, 6]
speed: 35 feet,  fly 50 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +31, __Will__ +27"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Weaknesses__ cold 10; __Resistances__ fire 15, poison 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|+2 Greater Striking Scimitar]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Firedamp Winds"
    desc: " (air,aura) 30 feet. DC 33 Fortitude check.\n\nSwirling winds of noxious, flammable gas surround a muurfeli. An open flame, spark, or similar fire effect in the area causes an explosion that deals 20d6 fire damage to all creatures in the aura (including the muurfeli) and temporarily disables the aura for 1 minute.\n\nWhen the muurfeli takes damage from an ability with the water trait or fails a saving throw against a water effect, their firedamp winds aura is disabled for 1 minute.\n\nA creature that enters or begins its turn in the aura must attempt a Fortitude save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature is [[Conditions/Sickened|Sickened 2]] and [[Conditions/Fatigued|Fatigued]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+29 (agile, finesse, magical, nonlethal, reach 10 feet)\n__Damage__  3d10 + 15 bludgeoning 2d6 poison"

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+31 (forceful, magical, reach 10 feet, sweep)\n__Damage__  3d6 + 17 slashing 2d6 poison"

  - name: "**Ranged** `pf2:1` Fetid Winds"
    desc: "+31 (air, magical, poison, range increment 20 feet)\n__Damage__  2d8 + 7 bludgeoning 2d8 + 5 poison"

  - name: "Arcane Innate Spells"
    desc: "DC 36, attack +28; __7th __  _[[Spells/Toxic Cloud|Cloudkill]]_; __5th __  _[[Spells/Illusory Creature|Illusory Creature]]_; __4th __  _[[Spells/Breathe Fire|Burning Hands (At Will)]]_, _[[Spells/Vapor Form|Gaseous Form]]_, _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_; __2nd __  _[[Spells/Enhance Victuals|Enhance Victuals (At Will)]]_\n__Constant__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The muurfeli can take on the form of an owl. The owl form always looks the same, but the muurfeli can choose to become either Tiny or Small in this form. This transformation doesn't change their Speed or the attack and damage bonuses of their Strikes, but might change the damage type their Strikes deal (typically to slashing).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."
 
```

```encounter-table
name: Muurfeli
creatures:
  - 1: Muurfeli
```



Whereas typical djinn can cleanse or clear areas with their arcane winds, the air magic of muurfeli is tainted by the Black Desert's noxious radiation and mixed with the realm's ambient fetid winds.

* * *

Before the Black Desert became a barren sandscape, cultures with grand magical traditions lived under its soaring roof. These communities eventually left the vault or died out, but the genies they summoned remained and became warped by the region's pervasive blightburn radiation. Now, these "blightburn genies" have bodies with features mirroring those of beasts that dwell in dark places, and their elemental lineages have been irreparably corrupted.
