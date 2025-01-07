---
title: "Grick"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.G6sFsTC5QjxvrxS9" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Grick"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Grick"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +10, Stealth: +10, Survival: +8"
abilityMods: [3, 4, 1, -3, 3, -1]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +10, __Ref__ +11, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Resistances__ physical 3 (double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  1d8 + 6 piercing"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+11 (agile, finesse)\n__Damage__  1d6 + 6 slashing"

  - name: "Unbalancing Blow"
    desc: "  Any creature a grick critically hits is [[Conditions/Off-Guard|Off-Guard]] against its attacks until the end of the grick's next turn."

  - name: "Vermicular Movement"
    desc: "  When a grick takes a Stride action to move half its Speed or less, that movement doesn't trigger reactions."
 
```

```encounter-table
name: Grick
creatures:
  - 1: Grick
```




