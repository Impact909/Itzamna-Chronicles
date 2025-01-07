---
title: "Wight Spell Sniper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Qp9icTN0aqMpiTZv" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Wight Spell Sniper"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Wight Spell Sniper"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
trait_03: [[wight]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Intimidation: +12, Religion: +14, Stealth: +16, Survival: +16"
abilityMods: [2, 5, 2, 2, 5, 1]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +17, __Will__ +15"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115, fueled by spite, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+1 Striking Composite Shortbow]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Fearless Sash|Fearless Sash]], 30x [[Equipment/Arrows|Arrows]], [[Equipment/Spellstrike Ammunition (Type II)|Spellstrike Ammunition (Type II)]]"
  - name: "Grave Weapon"
    desc: " (divine) The wight is bound to a dagger it was buried with. Other wights can be bound to different weapons."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile)\n__Damage__  1d8 + 8 slashing plus drain-life"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+18 (deadly d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  2d6 + 7 piercing plus drain-life"

  - name: "Divine Innate Spells"
    desc: "DC 24, attack +16; __4th __  _[[Spells/Harm|Harm]]_; __2nd __  _[[Spells/Harm|Harm]]_, _[[Spells/Noise Blast|Noise Blast]]_, _[[Spells/Revealing Light|Revealing Light]]_"

  - name: "Drain Life"
    desc: " (divine) When the wight sniper damages a living creature using an unarmed attack or ranged weapon, the sniper gains 2d6 temporary Hit Points, and the creature must succeed at a DC 22 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the wight sniper's attacks increase the value of the drained condition by 1 on a failed save, to a maximum of [[Conditions/Drained|Drained 4]].\n\n[[Bestiary Effects/Effect_ Drain Life|Effect: Drain Life]]"

  - name: "Drain the Prey"
    desc: " (divine) **Trigger** The wight spell sniper kills a living creature\n* * *\n\n**Effect** The wight spell sniper breathes in the essence of the slain creature, making it easier to sense and hunt similar prey. The wight chooses one of the creature's traits (excluding rarity or size). Until the wight uses this ability again, it gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] creatures with that trait and a +2 circumstance bonus to Survival checks to [[Actions/Track|Track]] creatures with that trait. The saving throw DCs of the wight's spells and abilities increase by 1 against creatures with the same trait."
 
```

```encounter-table
name: Wight Spell Sniper
creatures:
  - 1: Wight Spell Sniper
```


Variant wight

Wights are intelligent undead spawned through inescapable cycles of spite. This spite might come from their own malevolent will in life, or can be instilled by necromantic rituals, typically involving the desecration of burial sites. Wights usually haunt burial grounds, catacombs, or other places of the dead. Their hunger is targeted toward the living—those whose pumping hearts and ruddy warmth inspire visceral hatred.

As many types of wights exist as types of people from which they might be created. Hulking brutes, skittering sneaks, and cunning tinkers all make for different wights with different niches to fill. The environment, too, plays a part in determining a wight's special abilities and defenses. Frost wights, for instance, can be found in parts of the world where exposure is a common end and the resentment of being left alone in the wild is a common source of spite. Durable and sustained by void energy, wights can last in harsh environments without decaying the way some lesser undead do.

A single wight can wreak significant havoc if it is compelled to rise from its tomb. Because creatures slain under a wight's curse can become wights as well, all it takes is a single wight and a handful of unlucky graveyard visitors to create a veritable horde of these undead. Thus, canny priests and adventurers know that the best solution to a wight problem is swift and total eradication. Care must be taken, though, to destroy wight spawn before attempting to destroy the parent wight, for spawn without a master gain the ability to create spawn of their own.
