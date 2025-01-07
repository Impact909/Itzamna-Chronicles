---
title: "Blisterwell Gaoler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.42TW0h1sXQUCurxr" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Blisterwell Gaoler"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Blisterwell Gaoler"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[orc]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +13, Diplomacy: +10, Intimidation: +12, Medicine: +11, Stealth: +10"
abilityMods: [4, 3, 3, 1, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +10, __Will__ +15"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85; __Resistances__ mental 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Sap|+1 Sap]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Chain Shirt|Chain Shirt]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+15 (agile, finesse, versatile s)\n__Damage__  1d6 + 8 piercing"

  - name: "**Melee** `pf2:1` Sap"
    desc: "+15 (magical, sweep)\n__Damage__  1d8 + 8 slashing"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+13 (range increment 120 feet, reload 2)\n__Damage__  1d10 + 4 piercing"

  - name: "Disarming Rebuke"
    desc: "`pf2:2`  The Blisterwell gaoler attempts to [[Actions/Disarm|Disarm]] a creature, with a +2 circumstance bonus to the roll. On a success, the gaoler can also make a sap Strike against the target. Both attacks count toward his multiple attack penalty, but the penalty increases only after both attacks."

  - name: "Punish Prisoners"
    desc: "  The Blisterwell gaoler can quickly subdue underequipped foes, dealing an additional 1d6 precision damage with all Strikes against creatures that aren't wielding a weapon or shield. This damage applies to creatures even if they are using exceptional unarmed combat options, such as jaws, claws, or special Strikes granted by a stance."
 
```

```encounter-table
name: Blisterwell Gaoler
creatures:
  - 1: Blisterwell Gaoler
```




