---
title: "Dragonstorm Fire Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i3dpC5GEw6wgmmZP" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Dragonstorm Fire Giant"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Dragonstorm Fire Giant"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[giant]]
trait_03: [[humanoid]]
trait_04: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Low-Light Vision"
languages: "Common, Draconic, Jotun, Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +35, Intimidation: +35"
abilityMods: [9, 6, 7, 3, 5, 2]
speed: 35 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +33, __Ref__ +27, __Will__ +30"
hp: 400
health:
  - name: ""
  - name: HP
    desc: "400; __Immunities__  fire; __Weaknesses__ holy 20; __Resistances__ acid 20, electricity 20, cold 20, poison 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+2 Greater Striking Greatsword]], [[Equipment/Hide Armor|+2 Greater Resilient Hide Armor]], Sack With 5 Rocks"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Catch Rock|Catch Rock]]"
    desc: "`pf2:r`  **Requirements** The monster must have a free hand but can [[Actions/Release|Release]] anything it's holding as part of this reaction.\n\n**Trigger** The monster is targeted with a thrown rock Strike or a rock would fall on the monster.\n* * *\n\n**Effect** The monster gains a +4 circumstance bonus to its AC against the triggering attack or to any defense against the falling rock. If the attack misses or the monster successfully defends against the falling rock, the monster catches the rock, takes no damage, and is now holding the rock."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+35 (magical, reach 15 feet, versatile p)\n__Damage__  3d12 + 20 slashing 1d6 electricity"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+35 (range increment 120 feet)\n__Damage__  3d10 + 12 bludgeoning 1d6 electricity"

  - name: "Arcane Innate Spells"
    desc: "DC 40, attack +32; __3rd __  _[[Spells/Levitate|Levitate (At Will)]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "Dragonstorm Blade"
    desc: "`pf2:3` (divine) The dragonstorm fire giant raises one hand to the sky, channeling dragonstorm energy into the blade held in the other. The giant makes a greatsword Strike with a -2 circumstance penalty against each creature within its reach. It makes only one attack roll and compares the result against each creature's AC. This Strike deals an additional 1d8 acid, 1d8 cold, 1d8 electricity, 1d8 fire, and 1d8 poison damage and counts as two attacks for the giant's multiple attack penalty."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  The monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."
 
```

```encounter-table
name: Dragonstorm Fire Giant
creatures:
  - 1: Dragonstorm Fire Giant
```


Variant fire giant


