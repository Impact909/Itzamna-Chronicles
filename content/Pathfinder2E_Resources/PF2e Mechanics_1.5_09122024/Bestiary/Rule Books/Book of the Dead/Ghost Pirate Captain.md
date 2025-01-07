---
title: "Ghost Pirate Captain"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pOjW1G9y78UKQNN2" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Ghost Pirate Captain"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Ghost Pirate Captain"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghost]]
trait_04: [[incorporeal]]
trait_05: [[spirit]]
trait_06: [[undead]]
trait_07: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Diplomacy: +15, Intimidation: +17, Sailing Lore: +16"
abilityMods: [-5, 6, 0, 2, 3, 5]
speed:  fly 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +14, __Ref__ +18, __Will__ +15"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Curse Ye Scallywags!"
    desc: " (curse,divine) When the ghost pirate captain is reduced to 0 HP, all creatures within 60 feet are subjected to a DC 25 Will check [[Spells/Mariner's Curse|Mariner's Curse]] spell. The locations of those that critically fail are known to the ghost until the curse is removed. This curse ends if the ghost is permanently destroyed."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When the ghost pirate captain is destroyed, they re-form after 2d4 days within the ship or location they're bound to, fully healed. They can be permanently destroyed if their desires are fulfilled, which could involve being defeated in a great battle or ensuring their treasure has been hidden."

  - name: "Ship Bound"
    desc: "  The ghost is typically bound to a vessel, even one damaged beyond repair. They can't venture more than 120 feet away from the ship or site of its wreckage."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Cutlass"
    desc: "+20 (forceful, magical, sweep)\n__Damage__  2d6 + 11 void"

  - name: "**Ranged** `pf2:1` Ghostly Hand Crossbow"
    desc: "+20 (magical, range increment 60 feet)\n__Damage__  2d6 + 8 void"

  - name: "Combat Current"
    desc: "`pf2:2`  The ghost makes a Strike with its cutlass or hand crossbow, then Flies up to half their Speed and makes a Strike with the other attack. If they moved through an enemy when they Flew, that enemy is [[Conditions/Off-Guard|Off-Guard]] against the second Strike."

  - name: "Savvy Joinin' Me Crew?"
    desc: "`pf2:r` (divine) **Trigger** The ghost reduces a living creature to 0 Hit Points with a melee Strike\n* * *\n\n**Effect** The creature attempts a DC 25 Fortitude check save. If the creature fails its save, it remains conscious but is controlled by the ghost until it loses its dying condition. It continues to attempt recovery checks as normal for the dying condition. The effect ends if the creature loses the dying condition. If the creature dies while under this effect, it joins the ghost's undead crew in 1d4 days. If the ghost is destroyed before the creature dies, the creature is spared this terrible fate."
 
```

```encounter-table
name: Ghost Pirate Captain
creatures:
  - 1: Ghost Pirate Captain
```



Undead prowling the ocean on derelict ships have long been threats sailors keep an eye out for. Other than corporeal undead, some undead pirates take on an incorporeal form, especially if their bodies have been lost to the fishes. Captains of crews in particular are likely to return from the dead, perhaps on account of their strong personalities.

* * *

Tethered to the world after death by powerful emotions that haven't been resolved, ghosts haunt the living as sad echoes of their former selves.
