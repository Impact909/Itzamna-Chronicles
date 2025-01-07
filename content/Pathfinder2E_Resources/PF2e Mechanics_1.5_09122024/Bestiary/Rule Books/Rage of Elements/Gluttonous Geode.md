---
title: "Gluttonous Geode"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2YhrAcJwFWsJZbyn" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Gluttonous Geode"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Gluttonous Geode"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Stealth: +4, Survival: +6"
abilityMods: [3, -1, 3, -4, 1, -3]
speed: 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +4, __Will__ +6"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Crystal Teeth"
    desc: "+9 ()\n__Damage__  1d4 + 4 piercing plus attach"

  - name: "Attach"
    desc: "`pf2:2`  The geode Leaps up to 15 feet and makes a crystal teeth Strike. If it hits a creature larger than itself, it can attach to that creature. Doing so is like Grabbing the creature ([[Actions/Escape|Escape]] DC 17), but the geode moves with that creature rather than holding it in place. The geode is [[Conditions/Off-Guard|Off-Guard]] while attached. If the geode is killed or pushed away while attached to a creature, that creature takes 1 persistent bleed damage. Escaping the attached geode or removing the geode in other ways doesn't cause bleed damage."

  - name: "Gnaw"
    desc: "`pf2:1`  **Requirements** The geode is attached to a creature\n* * *\n\n**Effect** The geode deals 1d4+2 bludgeoning damage to the creature it's attached to (DC 17 Fortitude check save)."
 
```

```encounter-table
name: Gluttonous Geode
creatures:
  - 1: Gluttonous Geode
```



The vast ranks of earth elementals have been slow to respond to the return of the elemental lords and the Planes of Metal and Wood. These events have not broken the mountains, nor have they blown away the sands.

## Earthy Emotions

Earth elementals talk even less than most elementals. They're ponderous, weighing decisions so slowly they can crush the energy from a discussion. Their foremost concern is whether a situation can be endured. Though a rare or resplendent treasure might entice an earth elemental, it's difficult to spur any sense of urgency in them without the presence of an immediate threat.
