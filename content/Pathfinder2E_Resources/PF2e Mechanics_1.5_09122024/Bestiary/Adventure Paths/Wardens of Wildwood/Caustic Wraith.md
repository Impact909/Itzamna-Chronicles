---
title: "Caustic Wraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mvUtqFeNHvk2aStP" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Caustic Wraith"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Caustic Wraith"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
trait_04: [[wraith]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision, Lifesense (Imprecise) 60 Feet"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Intimidation: +21, Stealth: +19"
abilityMods: [-5, 6, 3, 3, 4, 6]
speed:  fly 40 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +16, __Ref__ +19, __Will__ +21"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  acid,  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Aggravating Aura"
    desc: " (acid,aura,mental) 10 feet. Acidic vapor surrounds the caustic wraith, making other creatures' bodies feel raw and especially sensitive to pain. A creature that begins in the area must succeed at a DC 28 Will check save or gain weakness 3 to all damage for 1 round (weakness 5 on a critical failure).\n* * *\n\n[[Bestiary Effects/Effect_ Aggravating Aura|Effect: Aggravating Aura]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Caustic Touch"
    desc: "+21 (acid, finesse, reach 10 feet, void)\n__Damage__  2d8 void plus drain-life 1d8 acid plus drain-life"

  - name: "Dissolve From the Inside"
    desc: "`pf2:2`  The caustic wraith reaches into the body of a creature within 10 feet, melting its organs and inflicting pain. The target takes 4d8 acid damage with a DC 28 Fortitude check save. On a critical failure, the creature is also [[Conditions/Sickened|Sickened 2]]."

  - name: "Drain Life"
    desc: " (divine) When the caustic wraith damages a living creature with its caustic touch Strike, the wraith gains 10 temporary Hit Points, and the target must succeed at a DC 28 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the caustic wraith increases the drained condition value by 1 on a failed save, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Wraith Spawn"
    desc: " (divine,unholy) A living humanoid slain by a caustic wraith rises as a wraith spawn after 1d4 rounds. This wraith spawn is under the command of the wraith that killed it. It doesn't have drain life or wraith spawn and becomes [[Conditions/Clumsy|Clumsy 2]]. After 24 hours, the wraith spawn dissipates and is destroyed."
 
```

```encounter-table
name: Caustic Wraith
creatures:
  - 1: Caustic Wraith
```




