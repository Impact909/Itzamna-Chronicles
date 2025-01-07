---
title: "Crystal Strider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VCFO048KibHk36uA" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Crystal Strider"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Crystal Strider"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +23, Nature: +20"
abilityMods: [7, 3, 5, 0, 4, 1]
speed: 45 feet,  climb 45 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +19, __Will__ +20"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ sonic 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Crystal Refraction"
    desc: "`pf2:0`  **Trigger** The crystal strider is targeted by a light effect\n* * *\n\n**Effect** The strider redirects the triggering effect to a different creature of its choice within 30 feet or absorbs the effect harmlessly, reducing the number of rounds left to recharge Release Light by 1."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Leg"
    desc: "+21 (reach 15 feet, versatile p)\n__Damage__  2d10 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Crystal Dart"
    desc: "+21 (range increment 30 feet)\n__Damage__  2d10 + 13 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 29, attack +21; __5th __  _[[Spells/Chromatic Ray|Chromatic Ray (Release Light)]]_"

  - name: "Precise Steps"
    desc: "  The crystal strider's many narrow legs allow it to ignore difficult terrain."

  - name: "Release Light"
    desc: "`pf2:1` (attack,light,primal) The strider emits the light that continually refracts within them to cast [[Spells/Chromatic Ray|Chromatic Ray]] as an innate primal spell heightened to 5th rank, with a +21 spell attack roll. The crystal strider can't Release Light again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, leg, DC 29 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Crystal Strider
creatures:
  - 1: Crystal Strider
```



Each long, thin leg of a crystal strider is a single enormous crystal, typically quartz or selenite. The strider uses this panoply of legs and a fluctuating physical structure to rapidly move about crystalline caverns, unimpeded by terrain.

* * *

The vast ranks of earth elementals have been slow to respond to the return of the elemental lords and the Planes of Metal and Wood. These events have not broken the mountains, nor have they blown away the sands.

## Earthy Emotions

Earth elementals talk even less than most elementals. They're ponderous, weighing decisions so slowly they can crush the energy from a discussion. Their foremost concern is whether a situation can be endured. Though a rare or resplendent treasure might entice an earth elemental, it's difficult to spur any sense of urgency in them without the presence of an immediate threat.
