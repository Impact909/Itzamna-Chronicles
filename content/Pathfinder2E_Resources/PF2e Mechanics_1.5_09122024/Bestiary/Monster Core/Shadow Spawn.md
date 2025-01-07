---
title: "Shadow Spawn"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2AXY5yxjo39OQLPz" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Shadow Spawn"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Shadow Spawn"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Stealth: +12"
abilityMods: [-5, 4, 0, -2, 2, 3]
speed:  fly 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +12, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, vitality, or spirit; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  Attacks against the shadow are treated as magical if made by a creature who is in magical light or with an object that is in magical light (such as from the [[Spells/Light|Light]] spell)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+15 (finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."
 
```

```encounter-table
name: Shadow Spawn
creatures:
  - 1: Shadow Spawn
```



The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light.
