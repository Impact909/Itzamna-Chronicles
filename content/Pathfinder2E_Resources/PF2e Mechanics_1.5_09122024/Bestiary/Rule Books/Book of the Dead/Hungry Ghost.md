---
title: "Hungry Ghost"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5sTPyQQMsACvq8a0" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Hungry Ghost"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Hungry Ghost"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: "Common, Necril; one other language"
skills:
  - name: "Skills"
    desc: "Deception: +14, Diplomacy: +14, Religion: +17, Ghost Lore: +18"
abilityMods: [-5, 5, 0, 4, 5, 4]
speed:  fly 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +12, __Ref__ +17, __Will__ +15"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Living Visage"
    desc: "  While they have more than 30 HP, the hungry ghost appears to be a living creature. They have an automatic result of 34 on Deception checks and DCs to conceal their undead status and can Feed on the Living covertly."

abilities_mid:
  - name: ""
  - name: "Feed on the Living"
    desc: "`pf2:2` (divine,void) The hungry ghost touches a creature in reach. If the target is a living creature, it takes damage from the ghost's ghostly touch with a DC 24 Fortitude check save. If the ghost is in their living visage, they can disguise Feed on the Living as a benign touch and delay the effects for 1 minute while keeping the target unaware of the effect. A creature can be affected by only one delayed Feed on the Living at a time, and if the ghost loses their living visage during that minute, the Feed on the Living is lost.\n* * *\n\n**Critical Success** The target's life energy overpowers the ghost. The hungry ghost takes 5 vitality damage, and the target is unaffected.\n\n**Success** The target takes half damage, and the hungry ghost regains HP equal to the damage dealt.\n\n**Failure** The target takes full damage and is [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute, and the hungry ghost regains HP equal to the damage dealt.\n\n**Critical Failure** The target takes double damage and is [[Conditions/Enfeebled|Enfeebled 2]] for 1 minute, and the hungry ghost regains HP equal to the damage dealt."

  - name: "Ravenous Undoing"
    desc: "  In each 24-hour period, the hungry ghost must use Feed on the Living to consume 30 HP (any HP the ghost would gain count toward this total, even if the ghost has enough HP that they don't actually regain the full amount). If the ghost hasn't consumed enough HP, they mindlessly and recklessly feed on any living creature they come across until satiated."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When destroyed, hungry ghosts reform after 2d4 days fully healed at whatever location they were at when last destroyed. They're only permanently destroyed when they have been given a proper burial, have had their grave cleaned and maintained for at least a year, or have been judged to be redeemed by Pharasma."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Touch"
    desc: "+17 (agile, finesse, magical)\n__Damage__  2d8 + 4 void"
 
```

```encounter-table
name: Hungry Ghost
creatures:
  - 1: Hungry Ghost
```



Hungry ghosts arise from those who didn't receive proper burials or whose graves were neglected. They are not bound to a site or item but are compelled to see opportunities to commit good deeds in hopes of gaining favors that can aid them in achieving a final rest. Their need to feed on living energy often conflicts with this goal, however.

* * *

Tethered to the world after death by powerful emotions that haven't been resolved, ghosts haunt the living as sad echoes of their former selves.
