---
title: "Ntavi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WlPxVRMKJh5MeSOv" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Ntavi"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Ntavi"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[human]]
trait_03: [[humanoid]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +14, Crafting: +12, Intimidation: +13, Society: +12, Survival: +13"
abilityMods: [4, 2, 3, 0, 1, 2]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +14, __Will__ +11"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Composite Longbow]], [[Equipment/Maul|+1 Maul]], [[Equipment/Chain Mail|Chain Mail]], 20x [[Equipment/Arrows|Arrows]], 2x [[Equipment/Healing Potion (Lesser)|Healing Potion (Lesser)]], 10x [[Equipment/Gold Pieces|Gold Pieces]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+16 (magical, shove)\n__Damage__  1d12 + 7 bludgeoning"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+16 (deadly d10, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 7 piercing"

  - name: "Furious Power Attack"
    desc: "`pf2:2`  Ntavi makes a melee Strike. This counts as one attack when calculating her multiple attack penalty. If the Strike hits, she deals an extra die of weapon damage."

  - name: "Maul Mastery"
    desc: "  Ntavi has access to the critical specialization effects for hammers."
 
```

```encounter-table
name: Ntavi
creatures:
  - 1: Ntavi
```




