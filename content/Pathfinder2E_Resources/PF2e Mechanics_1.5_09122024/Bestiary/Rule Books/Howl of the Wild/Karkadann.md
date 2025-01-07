---
title: "Karkadann"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hWhziAqFwJoml6W5" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/fey
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Karkadann"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Karkadann"
level: "Creature 7"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[fey]]
trait_03: [[holy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Diplomacy: +13, Intimidation: +15, Medicine: +14, Survival: +14"
abilityMods: [6, 3, 6, 0, 3, 4]
speed: 45 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +17, __Ref__ +14, __Will__ +14"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  poison"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Fearless Rush"
    desc: "`pf2:r`  **Trigger** The karkadann becomes [[Conditions/Frightened|Frightened]]\n* * *\n\n**Effect** The karkadann reduces their frightened value by 1 (to a minimum of 0). The karkadann then Strides toward an enemy."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+17 (holy, magical)\n__Damage__  2d10 + 8 piercing"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+17 (holy, magical)\n__Damage__  2d6 + 8 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +0; __3rd __  _[[Spells/Cleanse Affliction|Cleanse Affliction (x2)]]_; __1st __  _[[Spells/Cleanse Cuisine|Cleanse Cuisine (x3)]]_\n__Cantrips__  __(4th)__ _[[Spells/Light|Light]]_"

  - name: "Ghost Touch"
    desc: "  A karkadann's Strikes have the effects of a ghost touch property rune."

  - name: "Impaling Charge"
    desc: "`pf2:2`  The karkadann Strides twice, then Strikes with their horn. If the Strike hits, it also deals 1d10 persistent bleed damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, hoof, DC 25 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Karkadann
creatures:
  - 1: Karkadann
```




