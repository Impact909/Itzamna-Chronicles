---
title: "Scarlet Triad Bruiser"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M7Ai6EhC4k3Qdz2E" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Scarlet Triad Bruiser"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Scarlet Triad Bruiser"
level: "Creature 10"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +21, Intimidation: +18, Stealth: +19, Sailing Lore: +18"
abilityMods: [5, 3, 5, 0, 5, 2]
speed: 25 feet
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +17, __Will__ +19"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatclub|+1 Striking Greatclub]], [[Equipment/Shortbow|+1 Shortbow]], [[Equipment/Chain Shirt|Chain Shirt]], 3x [[Equipment/Manacles (Average)|Manacles (Average) (Marked with the Symbol of the Scarlet Triad)]], 10x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatclub"
    desc: "+22 (backswing, shove)\n__Damage__  2d10 + 1 bludgeoning plus knockdown"

  - name: "**Melee** `pf2:1` Kick"
    desc: "+21 (agile)\n__Damage__  1d8 + 11 bludgeoning"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+21 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  2d6 + 8 piercing"

  - name: "Batter the Fallen"
    desc: "  The Scarlet Triad Bruiser's kick Strikes deal 2d6 extra damage to [[Conditions/Prone|Prone]] creatures."

  - name: "Brutal Cleave"
    desc: "`pf2:r`  **Trigger** The bruiser's melee Strike kills a creature or knocks it [[Conditions/Unconscious|Unconscious]], and another foe is adjacent to that creature.\n* * *\n\n**Effect** The bruiser makes another melee Strike against the second foe at the same multiple attack penalty as the triggering Strike."

  - name: "Efficient Capture"
    desc: "`pf2:3` (attack,manipulate) **Requirements** The bruiser has manacles in hand and is adjacent to a creature.\n* * *\n\n**Effect** The bruiser attempts to bind the creature's wrists or ankles with the manacles. They must succeed at an attack roll with a +23 modifier against the target's AC."

  - name: "Pummeling Flurry"
    desc: "`pf2:1`  **Frequency** once per turn\n* * *\n\n**Effect** The bruiser makes a greatclub Strike and a kick Strike. If both hit the same creature, combine their damage for the purposes of resistances and weaknesses."
 
```

```encounter-table
name: Scarlet Triad Bruiser
creatures:
  - 1: Scarlet Triad Bruiser
```




