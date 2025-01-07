---
title: "Hateful Logger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wOoGeQpKcYDdbHsc" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Hateful Logger"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Hateful Logger"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Nature: +10, Survival: +10, Forest Lore: +12"
abilityMods: [4, 2, 4, 1, 0, 1]
speed: 25 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +12, __Will__ +8"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Weaknesses__ nonlethal attacks 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Hatchet|Hatchet]], [[Equipment/Padded Armor|Padded Armor]], [[Equipment/Climbing Kit|Climbing Kit]]"
abilities_mid:
  - name: ""
  - name: "Exhausted"
    desc: "  Though their minds are suffused with hatred and rage, the loggers have not slept for several days and are ready to drop. They take a –2 status penalty to saving throws against effects with the sleep trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (agile, nonlethal)\n__Damage__  1d4 + 8 bludgeoning"

  - name: "**Melee** `pf2:1` Bite"
    desc: "+14 ()\n__Damage__  1d6 + 8 piercing"

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The logger deals 1d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."

  - name: "Vitriol"
    desc: "`pf2:1` (curse,emotion,mental,occult) The hateful logger vomits a stream of caustic black sludge at a single foe it can detect within 15 feet. The logger and the target each gain a +1 circumstance bonus on all attack rolls made against each other until the logger chooses a different target for its Vitriol. The target must attempt a DC 19 Will check save, with the following effects. The logger cannot use Vitriol again for 1d4 rounds.\n* * *\n\n**Critical Success** No effect.\n\n**Success** The target's mind is clouded by feelings of rage and hate, causing it to be [[Conditions/Off-Guard|Off-Guard]] against the logger's next attack. It can't use actions with the concentrate trait unless they also have the rage trait.\n\n**Failure** As success, but the target is off-guard until the end of the logger's next turn. While off-guard, it is unable to use actions with the concentrate trait unless they also have the rage trait.\n\n**Critical Failure** As failure, but the target is off-guard until the logger chooses a different target for its Vitriol."
 
```

```encounter-table
name: Hateful Logger
creatures:
  - 1: Hateful Logger
```




