---
title: "Rezzelki"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aQ6NDheOBBxanESN" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Rezzelki"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Rezzelki"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[beast]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Osiriani; Can&#x27;t Speak"
skills:
  - name: "Skills"
    desc: "Athletics: +22"
abilityMods: [6, 3, 5, -3, 3, 2]
speed: 25 feet,  fly 20 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +21, __Ref__ +17, __Will__ +19"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175; __Resistances__ acid 10"
abilities_top:
  - name: ""

  - name: "Glutton Scent"
    desc: "  A rezzelki's scent ability becomes a precise sense against its favored meal."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Favored Meal"
    desc: "  All rezzelkis have a favorite type of creature to feast upon. Against a favored meal in combat, a rezzelki gains a +1 circumstance bonus to all Strikes and Athletics checks.\n\nIf an encounter doesn't specify what a rezzelki's favorite foodstuff is, roll 1d6:\n\n1—human\n\n2—dwarf\n\n3—elf\n\n4—kholo\n\n5—desert giant\n\n6—mummy"

  - name: "Reactive Taste"
    desc: "`pf2:r` (primal) **Trigger** A creature within reach of the rezzelki's tongue uses a manipulate or a move action, makes a ranged attack, or leaves a square during a move action it's using\n* * *\n\n**Effect** The rezzelki makes a tongue Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tail"
    desc: "+22 (forceful, magical)\n__Damage__  2d12 + 10 bludgeoning plus knockdown"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+22 (agile, reach 10 feet)\n__Damage__  2d6 + 6 slashing 1d6 acid"

  - name: "Primal Innate Spells"
    desc: "DC 29, attack +21\n__Constant__  __(5th)__ _[[Spells/Fly|Fly]]_"

  - name: "Fracturing Smash"
    desc: "`pf2:2` (attack) The rezzelki Strikes a target with a particularly powerful blow from its tail, with enough force to potentially pulverize bone. This Strike treats any object it hits as if it had half as much Hardness as usual, unless the object's hardness is greater than the rezzelki's level. If the Fracturing Smash hits, it deals two extra dice of weapon damage. A creature with a skeleton that takes damage must succeed at a DC 26 Fortitude check save or become [[Conditions/Clumsy|Clumsy 1]] ([[Conditions/Clumsy|Clumsy 2]] on a critical failure) by the Fracturing Smash as its bones are partially broken."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Rezzelki
creatures:
  - 1: Rezzelki
```



Rezzelkis are curious-looking beasts native to the deserts of Osirion. Three feet tall at the shoulder and five feet long, rezzelkis are squat, mammalian quadrupeds with tawny red fur, with crystal-studded flat tails, and prehensile anteater-like snouts. Their long, pink tongues are covered with hundreds of tiny, razor-sharp bristles that allow them to rasp through flesh with unnerving ease, even before accounting for the effect of their acidic saliva.

Rezzelkis are ferociously territorial and quick to attack anyone or anything they regard as intruding upon their territory. Yet they're also prone to strange gastronomic obsessions, and if someone can deduce a particular rezzelki's favorite food, it's possible to become the creature's ally by simply providing it regular access to its preferred meals. A specific rezzelki's favorite food is always a specific type of creature—some even prefer to dine exclusively on the dry bodies of undead like mummies—but most have a taste for a singular humanoid ancestry. Presented with a potential meal, the rezzelki moves quickly to smash its feast with its wide tail. Then it feeds upon the pulverized remains of the destroyed creature, slurping up battered flesh and powdered bones with a noisy gusto that has earned them a strange nickname in certain circles: "deathlicker."

## Rezzelki Hunger

While a rezzelki can subsist on any sort of pulverized creature's remains, they vastly prefer a specific type of creature and can sniff these potential meals out with alarming accuracy. If an encounter doesn't specify what a rezzelki's favorite foodstuff is, roll 1d6: 1—human, 2—dwarf, 3—elf, 4—kholo, 5—desert giant, 6—mummy. Rezzelkis found in regions other than Osirion certainly develop appetites for other types of creatures, of course!
