---
title: "Benthic Reaver"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bEZ1mRmNrkZeDPoI" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Benthic Reaver"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Impossible Lands"
name: "Benthic Reaver"
level: "Creature 21"
rare_03: [[Unique]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[evil]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 41
perception:
  - name: "Perception"
    desc: "+41; Darkvision, Truesight"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Arcana: +37, Athletics: +43, Nature: +37"
abilityMods: [10, 8, 7, 6, 8, 6]
speed: 30 feet,  swim 60 feet
sourcebook: "_Pathfinder Lost Omens: Impossible Lands_"
ac: 46
armorclass:
  - name: AC
    desc: "46 all-around vision; __Fort__ +38, __Ref__ +35, __Will__ +33"
hp: 500
health:
  - name: ""
  - name: HP
    desc: "500, void healing; __Immunities__  bleed,  cold,  death effects,  disease,  void,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ holy 20; __Resistances__ physical 10 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Intense Chill"
    desc: " (arcane,aura,cold) 30 feet. 5d6 cold damage (DC 41 Reflex check). On a failure, the creature takes a –15-foot status penalty to its Speeds for 1 round."

  - name: "Tail Sweep"
    desc: "`pf2:r`  **Trigger** A creature moves from beyond the reach of the benthic reaver's tail to within the reach of the benthic reaver's tail\n* * *\n\n**Effect** The benthic reaver makes a tail Strike against the triggering creature and can use Improved Knockdown if the attack hits, even if it isn't the benthic reaver's turn. If the benthic reaver knocks the target [[Conditions/Prone|Prone]], it disrupts the triggering move action."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+39 (reach 15 feet)\n__Damage__  2d6 void 4d12 + 18 piercing 2d6 cold"

  - name: "**Melee** `pf2:1` Fin"
    desc: "+39 (agile, reach 15 feet)\n__Damage__  2d6 void 4d8 + 18 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+39 (reach 30 feet)\n__Damage__  4d10 + 18 slashing plus improved-knockdown 2d6 void plus improved-knockdown"

  - name: "**Ranged** `pf2:1` Eye Beam"
    desc: "+37 (range 150 feet)\n__Damage__  4d12 + 8 cold 4d6 void"

  - name: "Arcane Innate Spells"
    desc: "DC 41, attack +33\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Numbing Ice"
    desc: " (cold) A creature who takes damage from the benthic reaver's eye beam Strike must succeed at a DC 41 Fortitude check save or become [[Conditions/Slowed|Slowed 2]] as cold stiffens its limbs. A flying creature who fails its save also descends safely to the ground below. This is forced movement."

  - name: "Song of the Lost"
    desc: "`pf2:1` (arcane,auditory,emotion,fear,mental) The benthic reaver unleashes a cry of mourning. All creatures within 60 feet must attempt a DC 41 Will check save to resist. The benthic reaver can't use Song of the Lost for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Stunned|Stunned 1]] with sympathy."

  - name: "Tail Sweep"
    desc: "`pf2:2`  The benthic reaver makes a tail Strike against each enemy within its reach. These attacks count toward the benthic reaver's multiple attack penalty, but the multiple attack penalty doesn't increase until after the benthic reaver makes all its attacks."

  - name: "[[Bestiary Ability Glossary/Improved Knockdown|Improved Knockdown]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature as a free action. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Benthic Reaver
creatures:
  - 1: Benthic Reaver
```



The benthic reaver is a 50-foot-tall undead monstrosity, its ribs rising like giant archways and its spine splitting into three tails.
