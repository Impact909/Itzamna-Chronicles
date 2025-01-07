---
title: "Decrepit Mummy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PFU0DoIH4pSyvubB" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Decrepit Mummy"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Decrepit Mummy"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[mummy]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Necril; any one language they knew in life"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Stealth: +9"
abilityMods: [3, 1, -2, -2, 4, 2]
speed: 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 17
armorclass:
  - name: AC
    desc: "17 (15 when crumbling); __Fort__ +6, __Ref__ +7, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Crumbling Form"
    desc: "  A decrepit mummy is barely cohesive. Once a decrepit mummy is reduced to fewer than half their Hit Points, or immediately upon being damaged by a critical hit, they start falling apart, reducing their Armor Class to 15."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 ()\n__Damage__  1d8 + 3 bludgeoning plus lesser-mummy-rot"

  - name: "Lesser Mummy Rot"
    desc: " (disease,divine,void) The damage from this disease can't be healed while a creature still has the disease. A creature killed by lesser mummy rot turns to dust and can't be resurrected except by a 7th-rank [[Spells/Resurrect|Resurrect]] ritual or similar magic\n\n**Saving Throw** DC 16 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 minute)\n\n**Stage 2** 2d6 void damage and [[Conditions/Stupefied|Stupefied 1]] (1 day)"
 
```

```encounter-table
name: Decrepit Mummy
creatures:
  - 1: Decrepit Mummy
```



If a mummy has been in combat, endured the ravages of time, or been exposed to the elements, it can be so damaged it barely functions. These mummies continue guarding their tombs until they are too broken to even move.

* * *

The versatility of mummification allows the creation of mummies through a wide range of methods—nature, ritual, alchemy, and combinations of all these.
