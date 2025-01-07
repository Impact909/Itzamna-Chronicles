---
title: "Hellshadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vHNFC551klE39lBV" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Hellshadow"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Hellshadow"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[fiend]]
trait_02: [[incorporeal]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Common, Diabolic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Intimidation: +27, Stealth: +25"
abilityMods: [-5, 6, 5, 4, 5, 8]
speed:  fly 40 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +25, __Will__ +22"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, void healing; __Immunities__  death effects,  disease,  fire,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ holy 10; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Brimstone Cloak"
    desc: " (aura,divine,fire,sanctified,unholy) 10 feet. The hellshadow constantly exudes a cloud of smoke that scorches flesh but leaves other materials unharmed. Living creatures who start their turn in this aura take 2d6 fire damage (DC 30 basic Reflex). On a critical failure, the creature is also [[Conditions/Sickened|Sickened 1]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Brimstone Tendrils"
    desc: "+27 (agile, finesse, fire, reach 15 feet, sanctified)\n__Damage__  3d8 + 6 fire plus clinging-smoke 2d6 void plus clinging-smoke"

  - name: "Divine Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Shadow Blast|Shadow Blast (Fire or Spirit only)]]_; __6th __  _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Divine Immolation|Divine Immolation]]_\n__Cantrips__  __(7th)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Void Warp|Void Warp]]_"

  - name: "Clinging Smoke"
    desc: " (divine) A creature that takes damage from the hellshadow's brimstone tendrils Strike has coils of the creature's smoke solidify around their body, impeding movement. The creature must attempt a DC 33 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The smoke solidifies as it coils around their limbs, imposing a –5-foot status penalty to all Speeds until the end of the creature's next turn.\n\n**Failure** As success, except –10 feet to speed and the creature is also [[Conditions/Clumsy|Clumsy 1]] until the end of their next turn.\n\n**Critical Failure** As failure, except the creature is also [[Conditions/Slowed|Slowed 1]] until the end of their next turn."
 
```

```encounter-table
name: Hellshadow
creatures:
  - 1: Hellshadow
```



When a group of diabolists or worshippers of an archdevil come to an ignominious end, their souls can sometimes be caught between life and death, unable or unwilling to pass on to the afterlife due to the humiliation of their untimely deaths. When enough closely-associated worshippers whose souls aren't already claimed in existing contracts meet such a fate, the spiritual "weight" of this shame can cause them to merge into a conglomeration of infernally-infused spirits—a hellshadow.

Hellshadows look like a bank of fire and smoke, yet the flames themselves are made of distorted bodies and faces. Although made of multiple souls, a hellshadow is a singular creature with one mind and typically one goal: to defeat as many enemies of their faith as they can in order to repay the shame of their humiliating deaths.

## Why Only Hell?

The nature of diabolic worship and the strict rules involved are a big part of the psychology of humiliation that causes devil worshippers to become hellshadows. This same mix of conditions is rarer among other fiendish cults, who are more likely to become more common undead after such a death. Non-diabolic– themed hellshadows are all but unknown as a result.
