---
title: "Zombie Snake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3s3cOGA5MSFhAkzu" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Zombie Snake"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Zombie Snake"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 2
perception:
  - name: "Perception"
    desc: "+2; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +5, Stealth: +5"
abilityMods: [3, 1, 2, -5, 0, -2]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +6, __Ref__ +3, __Will__ +2"
hp: 35
health:
  - name: ""
  - name: HP
    desc: "35, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Slow"
    desc: "  A zombie snake is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+7 ()\n__Damage__  1d6 + 3 piercing plus filth-fever"

  - name: "Filth Fever"
    desc: " (disease) The sickened and unconscious conditions from filth fever can't end or be reduced until the disease is cured\n\n**Saving Throw** DC 14 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1d4 hours)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** sickened 1 and [[Conditions/Slowed|Slowed 1]] (1 day)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 5** dead"
 
```

```encounter-table
name: Zombie Snake
creatures:
  - 1: Zombie Snake
```



At around 5 feet long, this massive, rotting serpent lacks potent venom, but its bite still injects putrid fluid that can cause infection.

* * *

Simple to create and varied in purpose, these shambling undead are often used for their strength and endless stamina to conduct boring, repetitive tasks.
