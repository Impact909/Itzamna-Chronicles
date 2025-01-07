---
title: "Dig-Widget"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.b2M9hP4AEwpufC3S" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Dig-Widget"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Dig-Widget"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +9, Stealth: +14, Thievery: +15"
abilityMods: [2, 5, 1, -5, 0, -5]
speed: 30 feet,  burrow 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +10, __Ref__ +14, __Will__ +7"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Infiltration Tools"
    desc: "  A dig-widget's face consists of a set of [[Equipment/Thieves' Toolkit (Infiltrator)|Infiltrator Thieves' Tools]]. They can be salvaged from a destroyed dig-widget with a successful DC 20 Crafting check check. On a failed check, the tools are destroyed."

abilities_mid:
  - name: ""
  - name: "Mechanical Vulnerability"
    desc: "  A creature with expert proficiency in Thievery can attempt a check to [[Actions/Disable a Device|Disable a Device]] to damage a dig-widget. The DC is 22, and each success deals 20 damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Drill"
    desc: "+14 (fatal d10, finesse)\n__Damage__  2d6 + 4 piercing 1d6 bleed"

  - name: "**Melee** `pf2:1` Corkscrew"
    desc: "+14 (finesse)\n__Damage__  2d8 + 4 piercing"

  - name: "Fastening Leap"
    desc: "`pf2:1`  The dig-widget Leaps up 20 feet onto a creature or object and attempts a corkscrew Strike against it. If the Strike damages the target, the dig-widget attaches to the target (typically to the back of a creature). This is similar to [[Bestiary Ability Glossary/Grab|Grabbing]] the creature, but the dig-widget moves with that creature rather than holding it in place. While attached, the dig-widget can't use its corkscrew. The dig-widget can be [[Actions/Shove|Shoved]] off, or it can detach itself with an Interact action."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A dig-widget's Strikes deal an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Dig-Widget
creatures:
  - 1: Dig-Widget
```



Thieves covet dig-widgets, specialized constructs built for infiltration. Each dig-widget contains numerous simple tools, including a set of mechanical devices that function as thieves' tools, two arms with drills, and two arms with corkscrews for attaching to and climbing surfaces. Once activated, these devices propel themselves forward. Though they have the full faculties typical of a construct, they usually follow a simple routine: avoid notice, pick any lock barring the path, dig past obstacles, and attack if caught. They're rarely left unattended, as a thief needs to be nearby to follow after-both to steal goods and to stop the dig-widget from engaging in further larceny once it's achieved its goal.

The source of a dig-widget's power is as much mechanical as it is magical. The gears and springs that provide a dig-widget mobility are an improvement over more primitive true clockwork creations (whose functions require constant winding to remain mobile), but at the cost of security, for a dig-widget's moving parts can be dismantled quickly by thieves and others with the proper training.
