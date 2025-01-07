---
title: "Rootridden"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Hccb7UhwSnCPKf6P" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Rootridden"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Rootridden"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Necril, Wildsong"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +18, Intimidation: +17, Nature: +16, Stealth: +18"
abilityMods: [6, 4, 4, 1, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +18, __Ref__ +16, __Will__ +14"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120, void healing; __Immunities__  bleed,  death effects,  disease,  poison,  unconscious,  paralyzed"
abilities_top:
  - name: ""

  - name: "Rooted"
    desc: "  A rootridden is bonded to a specific root network. If it's more than 300 feet from this network for at least 1 minute, it becomes [[Conditions/Sickened|Sickened 2]] until it's again within 300 feet of the root network for at least 1 minute."

  - name: "Walk the Roots"
    desc: "  The rootridden ignores the effects of difficult terrain caused by plants and fungi."

abilities_mid:
  - name: ""
  - name: "Root Spawn"
    desc: " (primal,unholy) A living creature slain by a rootridden that had a lower level than the rootridden rises as a new rootridden after 1d10 rounds, on its turn. This new rootridden is under the command of the rootridden that created it. If the creator is destroyed, any rootridden it created in the past 24 hours are destroyed as well, immediately collapsing into inert plant matter."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 ()\n__Damage__  2d12 + 8 piercing"

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+20 (reach 10 feet)\n__Damage__  2d8 + 8 bludgeoning plus root-rot-poison"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+20 (deadly d10, range increment 30 feet)\n__Damage__  4d8 void"

  - name: "Root Rot Poison"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check;\n\n**Maximum Duration** 8 rounds\n\n**Stage 1** 3d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 3d6 poison damage and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 3** 4d6 poison damage and [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 4** 4d6 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"
 
```

```encounter-table
name: Rootridden
creatures:
  - 1: Rootridden
```




