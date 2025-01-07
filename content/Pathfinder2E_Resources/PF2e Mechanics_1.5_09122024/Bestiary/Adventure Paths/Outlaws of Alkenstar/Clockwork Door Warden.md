---
title: "Clockwork Door Warden"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6smuTTtQE1Lu0BDt" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Clockwork Door Warden"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #179: Cradle of Quartz"
name: "Clockwork Door Warden"
level: "Creature 4"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10"
abilityMods: [4, 2, 2, -5, 4, -5]
speed: 25 feet
sourcebook: "_Pathfinder #179: Cradle of Quartz_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +10, __Ref__ +8, __Will__ +14"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 5, orichalcum 5; __Resistances__ physical 5 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Repeating Hand Crossbow|Repeating Hand Crossbow]], [[Equipment/Repeating Hand Crossbow Magazine|Repeating Hand Crossbow Magazine]]"
  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 19 Thievery check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+14 (reach 10 feet)\n__Damage__  2d6 + 7 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Repeating Hand Crossbow"
    desc: "+12 (range 60 feet, reload 0, repeating)\n__Damage__  1d6 + 3 piercing"

  - name: "Brace Door"
    desc: "`pf2:1`  The door warden holds shut an adjacent door. This ends the door warden's turn. Until the start of its next turn, as long as it remains functional and in the same square, other creatures trying to get through must succeed at a DC 21 Athletics check check to [[Actions/Force Open|Force Open]] the door."

  - name: "Slam Door"
    desc: "`pf2:r`  **Trigger** The door warden Pushes a creature through an open doorway\n* * *\n\n**Effect** The door warden slams the door shut on the creature"

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Clockwork Door Warden
creatures:
  - 1: Clockwork Door Warden
```



This mechanical humanoid serves the role of a gatekeeper or even a greeter, but its strength also enables it to repel unwanted visitors.

* * *

In the Grand Duchy of Alkenstar, the creation of constructs is complicated by the intermittent interference of the nearby Mana Wastes. Golems and animated objects depend on lengthy magical rituals that the magic-warping effects of the Wastes often disrupt, but clockwork constructs use far less magic in their creation. A clockwork device replaces magical intricacy with superb manufacturing skill, using magic only for the final acts of animating and powering the device. Skilled local creators and inventors rarely follow someone else's design, so most clockworks found in Alkenstar are custom creations with abilities designed for a specific purpose or individual's needs.
