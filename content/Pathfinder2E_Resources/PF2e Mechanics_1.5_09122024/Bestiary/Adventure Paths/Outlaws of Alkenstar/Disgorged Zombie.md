---
title: "Disgorged Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YAqYNbIDI5ND9tIg" 
tags:
  - pf2e/creature/type/electricity
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Disgorged Zombie"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Disgorged Zombie"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[electricity]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[zombie]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +15"
abilityMods: [5, 4, 2, -5, 2, -2]
speed: 25 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +17, __Will__ +11"
hp: 52
health:
  - name: ""
  - name: HP
    desc: "52, lightning powered, void healing; __Immunities__  death effects,  disease,  electricity,  paralyzed,  poison,  mental; __Weaknesses__ vitality 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Electricity Absorption"
    desc: "  For 1 minute after taking electricity damage, a shock zombie loses its usual [[Conditions/Slowed|Slowed 1]] condition, gains the ability to use reactions, and gains a +10-foot status bonus to its Speed.\n\n[[Bestiary Effects/Effect_ Electricity Absorption|Effect: Electricity Absorption]]"

  - name: "Lightning Powered"
    desc: "  Arcs of restorative electricity jolt between shock zombies. For each shock zombie within 30 feet, the shock zombie gains fast healing 2 (to a maximum of fast healing 10).\n\n[[Bestiary Effects/Effect_ Lightning Powered|Effect: Lightning Powered]]"

  - name: "Slow"
    desc: "  A shock zombie is typically [[Conditions/Slowed|Slowed 1]] and can't use reactions (but see electricity absorption)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+16 ()\n__Damage__  1d12 + 7 bludgeoning plus amnesia-venom 1d12 electricity plus amnesia-venom"

  - name: "Amnesia Venom"
    desc: " (mental,poison) **Saving Throw** DC 29 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** off-guard and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** [[Conditions/Confused|Confused]], off-guard, and [[Conditions/Clumsy|Clumsy 2]] (1 round)."
 
```

```encounter-table
name: Disgorged Zombie
creatures:
  - 1: Disgorged Zombie
```


Variant shock zombie

Shock zombies are hideous undead covered with bolts and electrical wiring. Most have two large electric coils mounted on their backs to absorb and project electricity. If uncontrolled, shock zombies often wander far afield in search of inventors' labs or lightning storms to draw power from. In a pinch, the natural electric currents inside living creatures more than suffice.
