---
title: "Hippopotamus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i96U9BEEAI02OThf" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Hippopotamus"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Hippopotamus"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +11, Survival: +11"
abilityMods: [6, 2, 6, -4, 4, -2]
speed: 25 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +9, __Will__ +11"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The hippopotamus can hold its breath for 5 minutes."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (deadly d10)\n__Damage__  2d8 + 8 piercing"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+13 ()\n__Damage__  1d10 + 8 bludgeoning"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  30 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "Capsize"
    desc: "`pf2:1` (attack) The hippopotamus tries to capsize an adjacent aquatic vessel of its size or smaller. The hippopotamus must succeed at an Athletics check with a DC of 25 (reduced by 5 for each size smaller the vessel is than the hippo) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, foot, DC 23 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Hippopotamus
creatures:
  - 1: Hippopotamus
```



Typical adult hippos move quickly on land and attack stealthily in the water. Though herbivorous, hippos are notoriously aggressive and territorial.
