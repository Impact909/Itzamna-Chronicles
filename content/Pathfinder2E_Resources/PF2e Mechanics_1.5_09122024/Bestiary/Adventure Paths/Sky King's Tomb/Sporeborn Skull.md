---
title: "Sporeborn Skull"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iMqcBIUEpeeO7ATb" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Sporeborn Skull"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Sporeborn Skull"
level: "Creature 2"

alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[fungus]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8"
abilityMods: [1, 4, 1, -5, 3, 0]
speed: 15 feet,  fly 30 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +5, __Ref__ +10, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  acid,  mental; __Weaknesses__ vitality 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Spore Explosion"
    desc: "  When destroyed, a sporeborn skull explodes in a blast of bone and toxic spores that deals 1d6 piercing damage plus 1d6 poison damage to each adjacent creature (DC 18 Reflex check save)."

  - name: "Stir the Spores"
    desc: "`pf2:r` (poison) **Frequency** once per 1d4 rounds\n\n**Trigger** The sporeborn skull takes bludgeoning, piercing, or slashing damage\n* * *\n\n**Effect** The impact scatters spores onto all creatures within 5 feet, making them [[Conditions/Sickened|Sickened 1]] (DC 18 Fortitude check negates)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Forehead"
    desc: "+10 (finesse)\n__Damage__  1d6 + 3 bludgeoning 1d6 poison"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+10 (acid, agile, range 20 feet)\n__Damage__  1d12 + 2 acid"
 
```

```encounter-table
name: Sporeborn Skull
creatures:
  - 1: Sporeborn Skull
```


Variant Flaming Skull

More dangerous than simple severed heads, these skulls are wreathed in unearthly flames.

* * *

Beheaded are the reanimated heads of decapitation victims. These mindless undead fly through the air or roll around to attack their prey.
