---
title: "Tallow Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3goTDddQS8kdKCA8" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Tallow Guardian"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Crown of the Kobold King"
name: "Tallow Guardian"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[construct]]
trait_02: [[mindless]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17"
abilityMods: [5, 0, 2, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: Crown of the Kobold King_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +11, __Will__ +13"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ cold 10; __Resistances__ fire 5, physical 5 (except bludgeoning)"
abilities_top:
  - name: ""

  - name: "Molten Wax"
    desc: "  All persistent fire damage caused by a tallow guardian comes from globs of molten hot tallow that cling to its foes. This tallow cools automatically after 4 rounds, or immediately if the creature takes any cold damage; once the tallow cools, the persistent fire damage ends."

abilities_mid:
  - name: ""
  - name: "Melt"
    desc: "  If a tallow guardian takes any fire damage, its body melts somewhat and becomes even more difficult to damage. Until the end of its next turn, its resistance to slashing and piercing damage increases to 10, and its resistance to bludgeoning damage increases to 5."

  - name: "Slowed by Cold"
    desc: "  If a tallow guardian takes any cold damage, it loses the benefits granted by melt and becomes [[Conditions/Slowed|Slowed 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (magical)\n__Damage__  2d8 + 8 bludgeoning plus grab 1d6 fire plus grab"

  - name: "Encase"
    desc: "`pf2:1` (attack) The tallow guardian attempts to pull a Medium or smaller creature it has [[Conditions/Grabbed|Grabbed]] into its body. The tallow guardian attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it encases the creature with its body. An encased creature is grabbed, is [[Conditions/Slowed|Slowed 1]], and must hold its breath or start suffocating. It takes 2d6 fire damage from the tallow guardian's molten hot wax when it's first encased, and at the end of each of its turns while it's encased.\n\nA tallow guardian can only have one encased creature at a time; if a tallow guardian encases a new creature, a previously encased creature is forced out of its body into an adjacent square of the creature's choice.\n\nAn encased creature can break free with a successful DC 22 check to [[Actions/Escape|Escape]]. An encased creature can attack the tallow guardian, but only with unarmed attacks or with weapons of light Bulk or less. The tallow guardian is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the tallow guardian takes 7 or more bludgeoning or slashing damage from an encased creature, the creature wrenches itself free. A creature that gets free by either method can immediately breathe and exits the tallow guardian's space, but it continues to take 1d6 persistent fire damage from the molten wax that clings to its body.\n\nIf a tallow guardian is destroyed, any creature it has encased is automatically released as the guardian's body collapses into a shapeless mound of tallow."
 
```

```encounter-table
name: Tallow Guardian
creatures:
  - 1: Tallow Guardian
```



A tallow guardian typically appears as a vaguely humanoid-shaped mass of tallow or wax, its surface constantly melting, running down its body, and then hardening only to be reabsorbed into the central mass. The tallow guardian's face seems constantly on the verge of melting into a shapeless blob, yet the unsettling construct can still sense the world around it with ease.
