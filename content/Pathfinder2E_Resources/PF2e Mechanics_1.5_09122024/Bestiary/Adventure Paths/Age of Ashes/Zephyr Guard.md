---
title: "Zephyr Guard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QbfQsRXCbWiLtP1A" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Zephyr Guard"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #149: Against the Scarlet Triad"
name: "Zephyr Guard"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +28, Diplomacy: +24, Intimidation: +24, Society: +22, Katapesh Lore: +24"
abilityMods: [8, 5, 5, 2, 4, 4]
speed: 25 feet
sourcebook: "_Pathfinder #149: Against the Scarlet Triad_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +26, __Will__ +29"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Heavy Crossbow|+1 Striking Heavy Crossbow]], [[Equipment/Scimitar|+2 Striking Scimitar]], [[Equipment/Breastplate|+1 Resilient Breastplate]], [[Equipment/Healing Potion (Greater)|Healing Potion (Greater)]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+30 (forceful, magical, sweep)\n__Damage__  2d6 + 14 slashing plus subduing-strikes"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+30 (magical, range increment 120 feet, reload 2)\n__Damage__  2d10 + 6 piercing plus subduing-strikes"

  - name: "Adroit Disarm"
    desc: "`pf2:2`  The Zephyr Guard attempts to [[Actions/Disarm|Disarm]] a creature, with a +2 circumstance bonus to the roll. On a critical success, the guard can also deal their [[Equipment/Scimitar|Scimitar]] damage to the creature."

  - name: "Hampering Shot"
    desc: "`pf2:2`  The Zephyr Guard makes a heavy crossbow Strike that deals one additional weapon damage die. If the Strike hits, the target takes a -10-foot status penalty to its Speeds and is [[Conditions/Slowed|Slowed 1]]. These last for 1 round, or 2 rounds if the Strike was a critical success."

  - name: "Subduing Strikes"
    desc: "  A Zephyr Guard takes no penalty for making nonlethal attacks with a weapon that doesn't have the nonlethal trait. The guard's nonlethal Strikes against a creature that is not wielding a weapon deal an additional 2d6 damage."
 
```

```encounter-table
name: Zephyr Guard
creatures:
  - 1: Zephyr Guard
```




