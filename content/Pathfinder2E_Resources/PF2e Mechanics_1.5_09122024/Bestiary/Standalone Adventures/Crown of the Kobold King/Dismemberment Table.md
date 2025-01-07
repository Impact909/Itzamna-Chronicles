---
title: "Dismemberment Table"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p6kRWsglm5ht5ab5" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Dismemberment Table"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Dismemberment Table"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13"
abilityMods: [5, 2, 4, -5, 0, -5]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 22
armorclass:
  - name: AC
    desc: "22 18 when broken; __Fort__ +13, __Ref__ +11, __Will__ +9"
hp: 56
health:
  - name: ""
  - name: HP
    desc: "56; __Hardness__ 8; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ vitality 8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Monster Core/Animated Armor/Construct Armor (Hardness 8)|Construct Armor (Hardness 8)]]"
    desc: "  Like normal objects, an animated armor has Hardness. This Hardness reduces any damage it takes by an amount equal to the Hardness. Once an animated armor is reduced to less than half its Hit Points, or immediately upon being damaged by a critical hit, its construct armor breaks and its Armor Class is reduced to 18."

  - name: "Haunted"
    desc: "  The dismemberment table is powered by unquiet spirits, and it takes damage from vitality energy as if it were undead. Vitality energy bypasses the table's hardness."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blade"
    desc: "+14 (magical)\n__Damage__  2d8 + 7 slashing"

  - name: "**Melee** `pf2:1` Strap"
    desc: "+14 ()\n__Damage__  2d4 + 7 bludgeoning plus grab"

  - name: "Disabling Strike"
    desc: "`pf2:1`  The dismemberment table attempts a blade Strike on a single target that it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]. If this Strike hits, the blade cuts deep into one of the target's limbs. The target must attempt a DC 22 Fortitude check save.\n* * *\n\n**Critical Success** The creature suffers no additional effect.\n\n**Success** The creature takes 1d6 bleed damage.\n\n**Failure** The creature takes 2d6 bleed damage and is [[Conditions/Clumsy|Clumsy 1]]. This clumsy condition ends once the creature is restored to full Hit Points.\n\n**Critical Failure** As failure, but [[Conditions/Clumsy|Clumsy 2]]."
 
```

```encounter-table
name: Dismemberment Table
creatures:
  - 1: Dismemberment Table
```


Variant animated object


