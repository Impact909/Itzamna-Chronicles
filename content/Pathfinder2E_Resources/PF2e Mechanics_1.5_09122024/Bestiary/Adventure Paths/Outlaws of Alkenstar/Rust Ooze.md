---
title: "Rust Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IaC5Xh5UoTwrwNHY" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Rust Ooze"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Rust Ooze"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9, Stealth: +5"
abilityMods: [4, -4, 3, -5, 1, -5]
speed: 15 feet,  swim 30 feet
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 11
armorclass:
  - name: AC
    desc: "11; __Fort__ +10, __Ref__ +3, __Will__ +6"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80; __Immunities__  critical hits,  precision,  unconscious,  visual,  mental; __Weaknesses__ electricity 5; __Resistances__ metal 5"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A rust ooze can sense nearby creatures through vibration and air or water movement."

abilities_mid:
  - name: ""
  - name: "Corrode Weapon"
    desc: "`pf2:r`  **Trigger** The rust ooze is hit with a metal weapon\n* * *\n\n**Effect** The rust ooze deals 2d6 acid damage to the item, ignoring its Hardness."

  - name: "Metal Resistance"
    desc: "  A rust ooze has resistance 5 to metal weapons."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+11 ()\n__Damage__  1d6 + 5 bludgeoning plus rust,tetanus"

  - name: "Rust"
    desc: "  When a rust ooze critically succeeds at a pseudopod Strike, it deals 2d6 acid damage to a metal item the target is wearing or holding, ignoring the item's Hardness. If a creature uses the Shield Block reaction with a metal shield against a rust ooze's pseudopod attack, the shield is automatically broken, but no other item is rusted."

  - name: "Tetanus"
    desc: " (disease) An infection introduced through open wounds, tetanus can produce stiffness, muscle spasms strong enough to break bones, and ultimately death.\n\n**Saving Throw** DC 14 Fortitude check\n\n**Onset** 10 days\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (1 week)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and can't speak (1 day)\n\n**Stage 3** [[Conditions/Paralyzed|Paralyzed]] with spasms (1 day)\n\n**Stage 4** death"
 
```

```encounter-table
name: Rust Ooze
creatures:
  - 1: Rust Ooze
```



Urban pollution breeds all kinds of new and interesting ooze creatures.

These reddish-brown globs wriggle through sewers and other waterways in search of iron pipes, metal trash, and other objects that rust.
