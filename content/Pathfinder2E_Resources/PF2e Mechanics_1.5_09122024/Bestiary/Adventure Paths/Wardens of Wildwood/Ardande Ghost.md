---
title: "Ardande Ghost"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.A6rE84k21hpYhvW1" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Ardande Ghost"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Ardande Ghost"
level: "Creature 11"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[wood]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Muan"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Nature: +19, Stealth: +21"
abilityMods: [-5, 6, 3, 2, 4, 6]
speed:  fly 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +24, __Will__ +15"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150, rejuvenation, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except ghost touch, force, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+23 (agile, finesse, magical)\n__Damage__  2d10 + 13 void plus phantom-blight"

  - name: "[[Creature Family Ability Glossary/(Ghost) Corrupting Gaze|Corrupting Gaze]]"
    desc: "`pf2:2`  The ghost stares at a creature it can see within 30 feet. The target takes 6d6 void damage with a DC 30 Will check save.\n\nA creature that fails its save is also [[Conditions/Stupefied|Stupefied 1]] for 1 minute."

  - name: "Phantom Blight"
    desc: " (mental,poison) **Saving Throw** DC 30 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d6 mental damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 4d6 mental damage and clumsy 1 (1 round)\n\n**Stage 3** 5d6 mental damage and clumsy 1, plus the creature takes a –2 penalty to saving throws against Ayrzul's Blight for 24 hours (1 round)"
 
```

```encounter-table
name: Ardande Ghost
creatures:
  - 1: Ardande Ghost
```




