---
title: "Xulgath Roughrider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ituz0ZFubyW4tWgX" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Xulgath Roughrider"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Xulgath Roughrider"
level: "Creature 11"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +22, Intimidation: +18, Nature: +21, Survival: +19, Dinosaur Lore: +16"
abilityMods: [5, 4, 3, -1, 4, 1]
speed: 30 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +22, __Ref__ +23, __Will__ +19"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|+1 Striking Halberd]], 6x [[Equipment/Javelin|Javelin]], [[Equipment/Hide Armor|Hide Armor]]"
abilities_mid:
  - name: ""
  - name: "Hasty Sacrifice"
    desc: "`pf2:r` (concentrate,move) **Prerequisite** The roughrider is mounted\n\n**Trigger** The roughrider is targeted with an attack from a creature they can see\n* * *\n\n**Effect** The roughrider's mount becomes the target of the attack instead. The roughrider must succeed at a DC 5 Flat check check or they fall off their mount and land [[Conditions/Prone|Prone]]. If the check is a critical failure, the roughrider also takes 1d6 bludgeoning damage in addition to the normal damage from the fall."

  - name: "Powerful Stench"
    desc: " (aura,olfactory) 30 feet. A creature that enters the area must attempt a DC 30 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 2]], and on a critical failure, the creature is also [[Conditions/Slowed|Slowed 1]] for as long as it is sickened. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stenches for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+24 (magical, reach, versatile s)\n__Damage__  2d10 + 11 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 ()\n__Damage__  2d8 + 11 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile)\n__Damage__  2d6 + 11 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+22 (thrown 30 ft.)\n__Damage__  1d6 + 11 piercing"

  - name: "Feral Directive"
    desc: "`pf2:2`  The xulgath attempts to [[Actions/Command an Animal|Command an Animal]] on their mount, but instead of demanding a specific action such as Stride or Strike, the xulgath gives a general directive, such as to return to camp or to attack a small group the mount can see. The mount and the xulgath each retain 3 actions on their turns, but the mount doesn't change its general tactics until the xulgath uses Feral Directive or Command an Animal again."

  - name: "Mounted Superiority"
    desc: "  A mounted xulgath's Strikes deal an additional 1d10 damage to creatures that aren't mounted."
 
```

```encounter-table
name: Xulgath Roughrider
creatures:
  - 1: Xulgath Roughrider
```




