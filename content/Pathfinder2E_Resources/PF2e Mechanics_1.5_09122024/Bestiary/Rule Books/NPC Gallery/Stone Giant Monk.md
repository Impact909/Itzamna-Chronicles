---
title: "Stone Giant Monk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WjBxIpODl2gGSdLz" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Stone Giant Monk"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Character Guide"
name: "Stone Giant Monk"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[earth]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[lawful]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Jotun"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +22, Intimidation: +16, Stealth: +16"
abilityMods: [6, 2, 4, 0, 1, 0]
speed: 40 feet
sourcebook: "_Pathfinder Lost Omens: Character Guide_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +16, __Will__ +16"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Sack with 5 Rocks"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+22 (agile, reach 10 feet)\n__Damage__  2d8 + 16 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+20 (brutal, range increment 120 feet)\n__Damage__  2d6 + 14 bludgeoning"

  - name: "Divine Focus Spells"
    desc: "2 Focus Points, DC 24, attack +16; __4th __  _[[Spells/Inner Upheaval|Ki Strike]]_, _[[Spells/Perfect Strike|Perfect Strike]]_"

  - name: "Big Swing"
    desc: "`pf2:2`  The stone giant makes a fist Strike. The target is [[Bestiary Ability Glossary/Push|Pushed]] up to 10 feet on a hit or up to 20 feet on a critical hit.\n\nIf the target collides with a solid object or lands on the ground, it takes bludgeoning damage as though it had fallen the distance it moved."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Stone Giant Monk
creatures:
  - 1: Stone Giant Monk
```




