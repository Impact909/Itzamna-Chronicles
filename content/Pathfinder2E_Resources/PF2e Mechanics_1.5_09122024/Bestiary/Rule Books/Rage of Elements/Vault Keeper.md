---
title: "Vault Keeper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t6Wq3l6e3bTJDLIo" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Vault Keeper"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Vault Keeper"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Tremorsense (Imprecise) 120 Feet"
languages: "Orvian, Petran; telepathy 300 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +26, Arcana: +26, Athletics: +26, Crafting: +26, Nature: +24, Thievery: +24, Planar Lore: +28"
abilityMods: [4, 8, 6, 8, 4, 6]
speed: 35 feet,  climb 35 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +24, __Ref__ +28, __Will__ +22"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200; __Immunities__  bleed,  paralyzed,  poison,  sleep,  radiation; __Resistances__ physical 15 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 300 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Craft Crystal Wand"
    desc: " (exploration) **Frequency** twice per day\n* * *\n\n**Effect** The vault keeper spends 10 minutes creating a magic wand out of radioactive green crystal, containing any 5th-rank or lower earth spell of their choice. The wand can be used by other creatures, but it crumbles to sand at the end of the day and has no monetary value."

  - name: "Item Caster"
    desc: "  The vault keeper can Cast a Spell from any item (such as a staff or wand) as though it were on their spell list."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+28 (agile, finesse, magical)\n__Damage__  3d10 + 10 slashing plus constraining-crystal"

  - name: "**Melee** `pf2:1` Crystal Wand"
    desc: "+28 (finesse, magical, radiation)\n__Damage__  3d4 + 10 piercing 4d6 poison"

  - name: "**Ranged** `pf2:1` Crystal Shard"
    desc: "+28 (earth, magical, range increment 100 feet)\n__Damage__  5d6 + 6 piercing"

  - name: "Arcane Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Petrify|Petrify]]_, _[[Spells/Summon Elemental|Summon Elemental (Earth Only)]]_, _[[Spells/Wall of Stone|Wall of Stone]]_; __6th __  _[[Spells/Scrying|Scrying]]_, _[[Compendium.pf2e.spells-srd.Item.nH3Rgzzv0b6IeKdd|Speak With Stones (At Will)]]_; __5th __  _[[Spells/Shatter|Shatter (At Will)]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Earthbind|Earthbind (At Will)]]_, _[[Spells/Shape Stone|Shape Stone (At Will)]]_, _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Constraining Crystal"
    desc: " (earth,magical) When the vault keeper deals damage with a claw Strike, glowing green crystals cluster at the site of the attack. The target must succeed at a DC 31 Fortitude check save or become [[Conditions/Clumsy|Clumsy 1]] for 1 hour (or [[Conditions/Clumsy|Clumsy 2]] on a critical failure). If the creature is already clumsy due to constraining crystal, additional failures increase that clumsy value instead, to a maximum of [[Conditions/Clumsy|Clumsy 4]]."

  - name: "Crystal Burst"
    desc: "`pf2:2` (arcane,earth) An explosion of razor-sharp splinters deals 15d6 piercing damage in a 30-foot burst within 120 feet, with a DC 35 Reflex check save. The vault keeper can't use Crystal Burst again for 1d4 rounds."

  - name: "Slashing Surge"
    desc: "`pf2:2`  The vault keeper Strides or Climbs and makes two claw Strikes at any point during that movement. Each Strike must target a different creature. The multiple attack penalty doesn't increase until after both attacks."
 
```

```encounter-table
name: Vault Keeper
creatures:
  - 1: Vault Keeper
```



The vault keepers lost Sairazul's spark and have life spans of two to three millennia. They maintain and protect the xiomorns' many experiments.

* * *

When Sairazul created xiomorns, they were immortal. She created 65,536, all in her own image, and all imbued with a piece of her divine spark. During her imprisonment, Ayrzul used visions of a future extinction to manipulate them into sacrificing their power to him. This sacrifice split xiomorns into two classes: 32,768 vault builders who kept Sairazul's essence and 32,768 vault keepers who would live forever no longer. For millennia, xiomorns built a vast, magical civilization across the Plane of Earth, and when there was no space left to build, they left. On each new world, xiomorns build their vaults and conduct their experiments, endlessly searching for clues to help them avoid their extinction.

## Vault Seeds

Xiomorns create magical underground caverns using vault seeds, ancient magical tools bequeathed to their species by Ayrzul as a reward for their sacrifice. The vault seeds were used to create the Vaults of Orv in Golarion's Darklands, and an accident involving an out-of-control vault seed created the mysterious Emerald Spire.

## Crystal Crafters

Xiomorns have mastered the creation of numerous magic items made of crystal beyond generation stones and vault seeds. These include pillars of black stone called whisperstones that allow xiomorns to communicate telepathically across vaults, orvgates that use weblike funnels of green crystal to allow teleportation between Darklands vaults, and a vortex in Orv called the Crystal Womb that connects to a crucial stronghold on the Plane of Earth.
