---
title: "Ararda"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.o58W1yKqTmYZgoMB" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/evil
  - pf2e/creature/type/genie
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Ararda"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Ararda"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[elemental]]
trait_03: [[evil]]
trait_04: [[genie]]
trait_05: [[lawful]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Petran, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Deception: +30, Intimidation: +30, Nature: +33, Survival: +33, Black Desert Lore: +27"
abilityMods: [9, 6, 7, 3, 7, 6]
speed: 30 feet,  burrow 45 feet,  fly 20 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +33, __Ref__ +30, __Will__ +31"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280; __Immunities__  disease; __Weaknesses__ sonic 20; __Resistances__ electricity 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Maul|+2 Greater Striking Maul]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Blightburn Radiation"
    desc: " (arcane,aura,disease) 60 feet. Blightburn crystals infused into an ararda's body attempt to counteract any teleportation spell moving into or out of the aura's emanation (counteract check +31; 7th level).\n\nIn addition, any creature that starts its turn within the emanation is exposed to Blightburn Sickness. The aura is blocked by lead sheeting, 1 foot of stone, or large force effects (such as a [[Spells/Wall of Force|Wall of Force]], but not a [[Spells/Shield|Shield]] spell).\n\nAn ararda can suppress their aura with an action (`pf2:1`) that has the concentrate trait."

  - name: "Charged Earth"
    desc: " (electricity) Any creature that hits an ararda with an unarmed attack or touches the ararda takes 2d8 electricity damage. Weapons that hit an ararda also take 2d8 electricity damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+35 (magical, reach 10 feet, shove)\n__Damage__  3d12 + 17 bludgeoning"

  - name: "**Melee** `pf2:1` Sand Fist"
    desc: "+35 (agile, earth, electricity, magical, nonlethal, reach 10 feet)\n__Damage__  2d8 + 17 bludgeoning plus blightburn-sickness 2d8 electricity plus blightburn-sickness"

  - name: "**Ranged** `pf2:1` Sand Spear"
    desc: "+32 (earth, electricity, magical, range increment 30 feet)\n__Damage__  4d8 piercing plus blightburn-sickness 2d8 electricity plus blightburn-sickness"

  - name: "Arcane Innate Spells"
    desc: "DC 37, attack +29; __7th __  _[[Spells/Chain Lightning|Chain Lightning]]_, _[[Spells/Petrify|Flesh to Stone]]_; __6th __  _[[Compendium.pf2e.spells-srd.Item.hkfH9Z53hPzcOwNB|Veil (Self Only)]]_, _[[Spells/Wall of Stone|Wall of Stone]]_; __5th __  _[[Spells/Shape Stone|Shape Stone (At Will)]]_; __4th __  _[[Spells/Vapor Form|Gaseous Form (Self Only)]]_, _[[Spells/Revealing Light|Glitterdust (x3)]]_\n__Constant__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_"

  - name: "Blightburn Sickness"
    desc: " (disease) Creatures native to the Black Desert are immune, as are creatures who are affected by blightburn sickness but recover from it. The target can't recover from the disease's drained or sickened condition except by magic.\n* * *\n\n**Saving Throw** DC 32 Fortitude check\n\n**Onset** 1d4 days\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] and [[Conditions/Sickened|Sickened 2]] (1 week)\n\n**Stage 4** [[Conditions/Drained|Drained 3]] and [[Conditions/Sickened|Sickened 3]] (1 month)\n\n**Stage 5** increase [[Conditions/Drained|Drained]] condition by 1 (1 year)"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (arcane,concentrate,polymorph) The ararda can take on the form of a scorpion. The scorpion form always looks the same, but the ararda can choose to become either Tiny or Small in this form. This transformation doesn't change their Speed or the attack and damage bonuses of their Strikes, but might change the damage type their Strikes deal (typically to piercing).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Earth Glide"
    desc: "  The aranda can [[Actions/Burrow|Burrow]] through dirt and stone at its full burrow Speed, leaving no tunnels or signs of its passing."
 
```

```encounter-table
name: Ararda
creatures:
  - 1: Ararda
```



Before the Black Desert became a barren sandscape, cultures with grand magical traditions lived under its soaring roof. These communities eventually left the vault or died out, but the genies they summoned remained and became warped by the region's pervasive blightburn radiation. Now, these "blightburn genies" have bodies with features mirroring those of beasts that dwell in dark places, and their elemental lineages have been irreparably corrupted.

* * *

Shaitans corrupted by the Black Desert's blightburn become scorpion-like arardas. While other earth genies sparkle with the iridescence of gemstones and evoke the power of the earth itself, arardas use their connection to the ground to harness the might of electricity. Arardas are so infused with this radioactive crystal that their mere presence is toxic to most living creatures.
