---
title: "Shadow (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZStLIISyUv5yEmsI" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Shadow (BB)"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Shadow (BB)"
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
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Stealth: +14"
abilityMods: [-5, 4, 0, -2, 2, 3]
speed:  fly 30 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  poison,  unconscious,  bleed,  void; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Incorporeal"
    desc: "  A shadow has no body and can pass through physical objects, though it can't end its turn inside one. Most checks that use Strength and require a body, such as [[Actions/Grapple|Grapple]] and [[Actions/Shove|Shove]], don't work against a shadow, and a shadow can't use them."

  - name: "Light Vulnerability"
    desc: "  Attacks against the shadow are treated as magical if the shadow or the weapon being used is in light."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+15 (finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a [[Monster Core/Shadow Spawn|Shadow Spawn]] under the command of the shadow that created it. This shadow spawn doesn't have Steal Shadow and is perpetually and incurably [[Conditions/Clumsy|Clumsy 2]]. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its [[Conditions/Enfeebled|Enfeeblement]], its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) If the shadow hit a living creature with a Strike on its previous action, it can use this action to pull at the target's shadow, imposing a -1 status penalty to Athletics and to attack rolls and damage rolls that use Strength. The penalty increases each time a shadow uses this ability to a maximum of -4. The penalty decreases by 1 every hour."
 
```

```encounter-table
name: Shadow (BB)
creatures:
  - 1: Shadow (BB)
```



Undead shadows feed on those who stray from the light.
