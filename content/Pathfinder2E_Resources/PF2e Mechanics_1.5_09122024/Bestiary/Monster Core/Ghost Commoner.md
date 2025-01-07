---
title: "Ghost Commoner"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3FUdmA1mZ2KgTszE" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Ghost Commoner"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ghost Commoner"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Stealth: +12, Dwelling Lore (applies to the place the ghost is bound to): +10"
abilityMods: [-5, 3, 0, 0, 2, 2]
speed:  fly 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +11, __Will__ +8"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, rejuvenation, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  A typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) Setting right the injustice that led to the commoner's death allows it to move on to the afterlife.\n* * *\n\nWhen a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+13 (agile, finesse, magical)\n__Damage__  2d6 + 2 void"

  - name: "[[Creature Family Ability Glossary/(Ghost) Frightful Moan|Frightful Moan]]"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The ghost laments its fate, forcing each living creature within 30 feet to attempt a DC 21 Will check save. On a failure, a creature becomes [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). On a success, a creature is temporarily immune to this ghost's frightful moan for 1 minute."
 
```

```encounter-table
name: Ghost Commoner
creatures:
  - 1: Ghost Commoner
```



The ghost commoner is an ordinary person who believes they died unjustly.

* * *

When some mortals die through tragic circumstances or without closure, their souls can linger and haunt a locale significant to them in life.
