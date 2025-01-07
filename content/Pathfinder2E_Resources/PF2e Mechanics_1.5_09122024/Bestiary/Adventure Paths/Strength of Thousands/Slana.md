---
title: "Slana"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.S064enaVkp5UaSyb" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Slana"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #174: Shadows of the Ancients"
name: "Slana"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[humanoid]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Low-Light Vision, Scent (Imprecise) 120 Feet"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +38, Nature: +35, Stealth: +33, Survival: +37"
abilityMods: [10, 7, 7, 2, 7, 6]
speed: 60 feet,  climb 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #174: Shadows of the Ancients_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +35, __Ref__ +33, __Will__ +33"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380, fast healing 20; __Immunities__  frightened; __Resistances__ sonic 30"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 20]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 20 feet, sonic)\n__Damage__  4d10 + 20 piercing plus improved-grab 2d8 sonic plus improved-grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 20 feet, sonic)\n__Damage__  4d6 + 20 piercing 2d8 sonic"

  - name: "**Ranged** `pf2:1` Thunderclap"
    desc: "+35 (magical, range increment 120 feet, sonic)\n__Damage__ "

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __10th __ (2 slots) _[[Spells/Earthquake|Earthquake]]_, _[[Spells/Storm Lord|Storm Lord (x3)]]_, _[[Spells/Storm of Vengeance|Storm of Vengeance]]_; __9th __ (4 slots) _[[Spells/Dispel Magic|Dispel Magic]]_; __1st __ (1 slots) _[[Spells/Mist|Obscuring Mist (At Will)]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "Great Roar"
    desc: "`pf2:2` (primal,sonic) The slana emits a deafening roar. All creatures within a 100-foot cone take 16d8 sonic damage (DC 44 Reflex check saving throw). On a failed save, a creature is also [[Conditions/Deafened|Deafened]] for 1 minute and [[Conditions/Stunned|Stunned 1]] (or deafened permanently and [[Conditions/Stunned|Stunned 3]] on a critical failure). The slana can't use Great Roar again for 1d4 rounds."

  - name: "Pounce"
    desc: "`pf2:1`  The slana Strides and makes a Strike at the end of that movement. If the slana began this action [[Conditions/Hidden|Hidden]], they remain hidden until after the ability's Strike."

  - name: "Thunder Trap"
    desc: "  A creature hit by the slana's thunderclap attack is [[Conditions/Immobilized|Immobilized]] and held in place by reverberations of sound until it Escapes or Forces Open the bonds of thunder that constrain it (DC 44). The target is [[Conditions/Deafened|Deafened]] as long as it is immobilized by a thunder trap."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Slana
creatures:
  - 1: Slana
```



The rolling thunder before the rain provides the massive, leonine humanoids known as slanas with a tremendous power. These solitary and nomadic creatures primarily dwell in the jungles and savannas of the Mwangi Expanse, but they can range into nearby areas in search of prey or when drawn by strange primal forces only slanas can recognize. Slanas view each other as rivals who test each other's prowess, so when drawn together by this strange calling they nearly always fight to the death. A slana's roar echoes like thunder across the countryside, and denizens of the Mwangi fear a slana's approach whenever an oncoming storm's thunder seems more ferocious than its rain.
