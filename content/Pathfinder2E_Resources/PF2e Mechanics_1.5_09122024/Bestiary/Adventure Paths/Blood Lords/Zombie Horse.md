---
title: "Zombie Horse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dt3NuidLLJMAcsN1" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Zombie Horse"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Zombie Horse"
level: "Creature 1"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +7"
abilityMods: [5, -1, 4, -5, 0, -2]
speed: 30 feet
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +6, __Ref__ +3, __Will__ +4"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d8 + 4 piercing"

  - name: "Chomp at the Bone"
    desc: "`pf2:1`  **Requirements** The zombie horse's previous action was a jaws Strike that dealt damage to its target\n* * *\n\n**Effect** the zombie horse makes a second jaws Strike as it violently gnashes its teeth and bites deep into the target's flesh. On a success, the target takes an additional 1d4 persistent bleed damage."

  - name: "Feast"
    desc: "`pf2:2` (manipulate) If the zombie horse is adjacent to a helpless or [[Conditions/Unconscious|Unconscious]] creature, or a deceased creature that died in the past hour, the zombie can feast upon its flesh to heal itself. This restores 1 healing Hit Point. If the creature is alive, the zombie horse deals damage equal to its jaws damage."
 
```

```encounter-table
name: Zombie Horse
creatures:
  - 1: Zombie Horse
```




