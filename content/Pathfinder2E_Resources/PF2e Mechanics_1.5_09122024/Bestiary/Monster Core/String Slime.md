---
title: "String Slime"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.reTUjyt8VSiQdejI" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "String Slime"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "String Slime"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11"
abilityMods: [4, -5, 5, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 10
armorclass:
  - name: AC
    desc: "10; __Fort__ +12, __Ref__ +0, __Will__ +5"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  acid,  critical hits,  precision,  slashing,  unconscious,  visual,  bleed,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A string slime can feel nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
  - name: "Split"
    desc: "  Whenever a string slime would take slashing damage (if it weren't immune) and has at least 10 HP, it splits into two identical slimes with half the original's HP. One string slime is in the same space as the original, and the other appears in an adjacent unoccupied space. If no adjacent space is unoccupied, move smaller creatures and objects out of the way to make a space or the split is canceled at the GM's discretion."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+11 ()\n__Damage__  1d8 + 4 bludgeoning 1d6 acid"

  - name: "Tag Team"
    desc: "`pf2:2`  **Requirements** another string slime is within 30 feet\n* * *\n\n**Effect** The slime arcs protoplasm to the other string slime. Creatures in that line take 3d6 acid damage with a DC 16 Reflex check save. A creature that fails its save is also knocked [[Conditions/Prone|Prone]]."

  - name: "Weak Acid"
    desc: "  A string slime's acid damages only organic material—not metal, stone, or other inorganic substances."
 
```

```encounter-table
name: String Slime
creatures:
  - 1: String Slime
```



Found underground or in dungeons, these quivering, slug-like ropes of slime continuously scour their domain for food. In addition to their shape, they are named for their ability to shoot out expanding ribbons of slime that resemble tangled strings.

* * *

Slimes, molds, and other oozes can be found in dank dungeons and shadowed forests. While not necessarily evil, some grow to enormous sizes and have insatiable appetites.
