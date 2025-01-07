---
title: "Kapoacinth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.orC7a7VV8jVeP3mx" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/earth
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Kapoacinth"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Kapoacinth"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[aquatic]]
trait_02: [[beast]]
trait_03: [[chaotic]]
trait_04: [[earth]]
trait_05: [[evil]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Petran, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +10, Stealth: +11"
abilityMods: [4, 1, 3, -2, 2, -2]
speed: 25 feet,  swim 40 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +9, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Resistances__ physical 5 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Wing Buffet"
    desc: "`pf2:r`  **Trigger** An adjacent creature attacks the kapoacinth while the kapoacinth is Swimming\n* * *\n\n**Effect** The kapoacinth pushes the triggering creature 5 feet away from them, and the kapoacinth moves 10 feet in the opposite direction. If the triggering creature can no longer attack the kapoacinth from its new location, the attack misses."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d8 + 6 piercing"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+13 (agile)\n__Damage__  2d6 + 6 slashing"

  - name: "Coral Reef"
    desc: "`pf2:1` (concentrate) Until the next time they act, the kapoacinth appears to be a lump of coral. They have an automatic result of 31 on Deception checks and DCs to pass as coral."
 
```

```encounter-table
name: Kapoacinth
creatures:
  - 1: Kapoacinth
```


Variant gargoyle


