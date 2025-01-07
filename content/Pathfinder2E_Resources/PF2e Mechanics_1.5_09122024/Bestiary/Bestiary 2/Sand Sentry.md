---
title: "Sand Sentry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nY65vd8OtAupGMzp" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Sand Sentry"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Sand Sentry"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Stealth: +14"
abilityMods: [5, 2, 4, 0, 2, 1]
speed: 25 feet,  burrow 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +12, __Will__ +14"
hp: 94
health:
  - name: ""
  - name: HP
    desc: "94; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Glass Armor"
    desc: "  When the sand sentry takes fire or lightning damage, its outer layer of sand fuses into sheets of hardened glass for 1 minute. This increases the sand sentry's AC to 26 and grants it resistance 5 to acid, cold, electricity, fire, force, piercing, and slashing damage. A sand sentry can't use earth glide while glass armor is active."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 ()\n__Damage__  2d8 + 8 bludgeoning plus blinding-sand"

  - name: "Blinding Sand"
    desc: "  When the sand sentry critically hits with a fist Strike, the target is [[Conditions/Blinded|Blinded]] for 1 round."

  - name: "Earth Glide"
    desc: "  A sand sentry can [[Actions/Burrow|Burrow]] through earthen matter, including rock. When it does so, it moves at its full burrow Speed, leaving no tunnels or signs of its passing."
 
```

```encounter-table
name: Sand Sentry
creatures:
  - 1: Sand Sentry
```



Shifting back and forth between a detailed likeness of a human and a muted and featureless bipedal form, this creature of pure sand moves with an eerie grace. The sand sentry is often called upon by spellcasters to stand guard over an area of great importance-these elementals are patient participants in such roles, making them well suited for long-term service.
