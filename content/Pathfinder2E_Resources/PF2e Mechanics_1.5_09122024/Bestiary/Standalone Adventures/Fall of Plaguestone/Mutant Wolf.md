---
title: "Mutant Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DPKyDibbKu3XloEE" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Mutant Wolf"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Fall of Plaguestone"
name: "Mutant Wolf"
level: "Creature 3"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Motion Sense (Precise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +11, Stealth: +9"
abilityMods: [4, 4, 2, -4, 2, -2]
speed: 35 feet
sourcebook: "_Pathfinder Adventure: The Fall of Plaguestone_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +9, __Ref__ +11, __Will__ +7"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  acid,  visual"
abilities_top:
  - name: ""

  - name: "Motion Sense (Precise) 30 feet"
    desc: "  A mutant wolf can sense nearby motion through vibration and air movement."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d8 + 4 piercing plus tear 1d6 acid plus tear"

  - name: "Gore Spray"
    desc: "`pf2:r` (acid) **Trigger** A creature critically hits a mutant wolf while adjacent to it.\n* * *\n\n**Effect** The wound causes gore to spray from a ruptured pustule. The triggering creature takes 3d6 acid damage (DC 19 Reflex check save). This occurs even if the attack kills the wolf."

  - name: "Tear"
    desc: "`pf2:1`  **Trigger** The wolf dealt damage to a creature with its jaws during the previous action.\n* * *\n\n**Effect** The wolf tears at the creature's flesh, dealing 1d6+2 slashing damage and 1 persistent acid damage."
 
```

```encounter-table
name: Mutant Wolf
creatures:
  - 1: Mutant Wolf
```




