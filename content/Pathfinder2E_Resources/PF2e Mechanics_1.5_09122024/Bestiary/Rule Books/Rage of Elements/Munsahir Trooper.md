---
title: "Munsahir Trooper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3lzCWsuBkHzoOZGq" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/fire
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Munsahir Trooper"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Munsahir Trooper"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[elemental]]
trait_02: [[fire]]
trait_03: [[humanoid]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Pyric"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Crafting: +11, Stealth: +12, Plane of Fire Lore: +11"
abilityMods: [3, 1, 5, 2, 3, 1]
speed: 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +6, __Will__ +11"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65; __Immunities__  fire; __Weaknesses__ cold 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|Warhammer]], [[Equipment/Dueling Pistol|Dueling Pistol]], [[Equipment/Breastplate|Breastplate]], 20x [[Equipment/Rounds (Dueling Pistol)|Rounds (Dueling Pistol)]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Heat of the Forge"
    desc: " (aura,fire) 10 feet. An munsahir's skin radiates heat like a forge's fire. A creature that starts its turn in the area must succeed at a DC 20 Fortitude check save or become [[Conditions/Fatigued|Fatigued]] while it remains in the area. Creatures immune to environmental heat effects or with any fire resistance are immune."

  - name: "Self-Destruct"
    desc: "  When the munsahir is reduced to 0 HP, their armor explodes at the start of their next turn, dealing 5d6 fire damage in a 10-foot emanation (DC 19 Reflex check)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+14 (shove)\n__Damage__  1d8 + 9 bludgeoning"

  - name: "**Ranged** `pf2:1` Dueling Pistol"
    desc: "+12 (concealable, concussive, fatal d10, range increment 60 feet, reload 1)\n__Damage__  1d6 + 6 piercing"

  - name: "Burning Touch"
    desc: " (fire,primal) The munsahir gatecrasher's Strikes deal an extra 1d6 fire damage (included above). When the gatecrasher successfully performs a [[Actions/Grapple|Grapple]] or [[Actions/Shove|Shove]] action, they also deal 1d6 fire damage to their target."

  - name: "[[Bestiary Ability Glossary/Power Attack|Volcanic Hammer]]"
    desc: "`pf2:2`  The trooper makes a warhammer Strike that deals one extra weapon die of damage and 2d6 persistent fire damage."
 
```

```encounter-table
name: Munsahir Trooper
creatures:
  - 1: Munsahir Trooper
```



Highly skilled troopers mostly come from the bronze class.

* * *

Munsahirs build militaristic, traditional societies.

## Munsahir Hierarchy

The three strata of munsahir society can be observed in the kilts worn by all members. Nobles, the unimpeachable rulers, wear elaborate brass kilts. In the middle of society are businesspeople and traders bedecked in bronze. Raw copper adorns those in the working class, who do most of the building and hard labor for munsahir society. Officially speaking, there is no class mobility; horrible crimes might cause a brass noble to be sent to prison but can't cause them to lose their station.
