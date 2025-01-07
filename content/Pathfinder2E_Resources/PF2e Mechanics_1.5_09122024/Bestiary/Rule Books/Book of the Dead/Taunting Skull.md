---
title: "Taunting Skull"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1AXlzNmLPBqZjea7" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Taunting Skull"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Taunting Skull"
level: "Creature 5"

alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: "Common, Necril; any one language spoken in life"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Intimidation: +12"
abilityMods: [1, 5, 1, 0, 4, 1]
speed: 15 feet,  fly 40 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +10, __Ref__ +14, __Will__ +11"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Bite Back"
    desc: "`pf2:r`  **Trigger** The taunting skull is attacked by a creature within their reach\n* * *\n\n**Effect** The taunting skull makes a jaws Strike against that creature."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 (agile, finesse, reach 0 feet)\n__Damage__  2d10 + 3 piercing"

  - name: "Incessant Goading"
    desc: "`pf2:1` (auditory,emotion,incapacitation,mental) The skull chooses one creature within 60 feet and antagonizes it mercilessly. The target must attempt a DC 22 Will check save to resist the effect.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune for 1 minute.\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Off-Guard|Off-Guard]] for 1 round. On its next turn, if the taunting skull is within the target's reach, the target wildly attacks the taunting skull as many times as possible.\n\n**Critical Failure** As failure, but the target also immediately performs a Strike against itself; this Strike doesn't take any actions."
 
```

```encounter-table
name: Taunting Skull
creatures:
  - 1: Taunting Skull
```



Some beheaded are raised with their mental faculties mostly intact. These clever undead often provoke their victims into foolishly giving chase or harming themselves.

* * *

Beheaded are disembodied floating heads transformed into undead. They are natural candidates for a necromancer's "project minion," due to the inexpensive cost of creation and endlessly customizable nature. In any lair occupied for long by practicing necromancers, it isn't uncommon to find a handful of floating heads roaming about, each exhibiting completely different characteristics and even degrees of expertise in their creation.
