---
title: "Clockwork Assassin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ryMudY3IHqsLHFI2" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Clockwork Assassin"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Clockwork Assassin"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Athletics: +25, Stealth: +27"
abilityMods: [6, 8, 4, -5, 0, -5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +23, __Ref__ +29, __Will__ +19"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 15, orichalcum 15; __Resistances__ physical 10 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Attack of Opportunity"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Integrated Launcher"
    desc: "  A projectile launcher is integrated into a clockwork assassin's systems, containing 10 spinning blades and five smoke bombs. When the assassin is destroyed, the launcher and its ammunition are also destroyed."

  - name: "Smoke Vision"
    desc: "  The clockwork assassin ignores the concealed condition from smoke."

  - name: "Wind-Up"
    desc: "  For the clockwork assassin to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. The assassin can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).A creature can attempt a DC 31 Thievery check check to Disable a Device to wind the assassin down. For each success, the assassin loses 1 hour of operational time. This can be done even if the assassin is in standby mode."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier Hand"
    desc: "+27 (deadly d8, disarm, finesse, magical)\n__Damage__  3d6 + 12 piercing plus unbalancing-blow"

  - name: "**Ranged** `pf2:1` Spinning Blade"
    desc: "+27 (agile, deadly d10, magical, range increment 120 feet)\n__Damage__  2d10 + 9 slashing"

  - name: "Rapid Repair"
    desc: " (manipulate) The clockwork assassin spends 1 hour of its operational time to repair itself, regaining 25 Hit Points and refilling its integrated projectile launcher with 4 spinning blades (to a maximum of 10) and 2 smoke bombs (to a maximum of 5)."

  - name: "Smoke Bomb Launcher"
    desc: "`pf2:1` (manipulate) The clockwork assassin launches a smoke bomb. A screen of thick, opaque smoke fills a 10-foot burst within 60 feet of the clockwork assassin. Creatures within the area are concealed, and all other creatures are concealed to them. The smoke lasts for 1 minute or until dispersed by a strong wind."

  - name: "Sneak Attack"
    desc: "  The clockwork assassin's Strikes deal an additional 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Unbalancing Blow"
    desc: "  Creatures hit by the clockwork assassin's rapier hand Strike are [[Conditions/Off-Guard|Off-Guard]] until the start of the clockwork assassin's next turn."
 
```

```encounter-table
name: Clockwork Assassin
creatures:
  - 1: Clockwork Assassin
```




