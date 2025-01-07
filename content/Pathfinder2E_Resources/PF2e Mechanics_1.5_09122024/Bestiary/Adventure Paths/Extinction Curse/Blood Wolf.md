---
title: "Blood Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TG2iy2H06E2TAJwg" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Blood Wolf"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Blood Wolf"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +10, Intimidation: +8, Stealth: +8, Survival: +9"
abilityMods: [5, 3, 2, -4, 2, -1]
speed: 30 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +9, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Weaknesses__ holy 3; __Resistances__ electricity 5, poison 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (unholy)\n__Damage__  1d8 + 5 piercing plus knockdown,pack-attack"

  - name: "Aggressive Rush"
    desc: "`pf2:1` (move) The blood wolf moves up to half its Speed. This movement doesn't trigger reactions. At the end of the movement, it attempts an Intimidation check to [[Actions/Demoralize|Demoralize]] a target within 5 feet of it. This Intimidation check doesn't take the -4 circumstance penalty for the wolf not speaking a language."

  - name: "Pack Attack"
    desc: "  The blood wolf's Strikes deal an extra 1d6 damage to creatures within reach of at least two of the wolf's allies."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Blood Wolf
creatures:
  - 1: Blood Wolf
```




