---
title: "Clockwork Injector"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lgO6hjWvDirtVVCM" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Clockwork Injector"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Clockwork Injector"
level: "Creature 15"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +27, Stealth: +29"
abilityMods: [6, 8, 4, -5, 0, -5]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +25, __Ref__ +31, __Will__ +21"
hp: 250
health:
  - name: ""
  - name: HP
    desc: "250; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 15, orichalcum 15; __Resistances__ physical 10 (except adamantine or orichalcum)"
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
    desc: "  For the clockwork assassin to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. The assassin can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).A creature can attempt a DC 33 Thievery check check to Disable a Device to wind the assassin down. For each success, the assassin loses 1 hour of operational time. This can be done even if the assassin is in standby mode."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Rapier Hand"
    desc: "+29 (deadly d8, disarm, finesse, magical)\n__Damage__  3d6 + 16 piercing plus unbalancing-blow"

  - name: "**Melee** `pf2:1` Syringe"
    desc: "+29 (magical, reach 10 feet)\n__Damage__  4d6 + 12 piercing 1d12 acid"

  - name: "**Ranged** `pf2:1` Spinning Blade"
    desc: "+29 (agile, deadly d10, magical, range increment 120 feet)\n__Damage__  2d10 + 13 slashing"

  - name: "Rapid Repair"
    desc: " (manipulate) The clockwork assassin spends 1 hour of its operational time to repair itself, regaining 25 Hit Points and refilling its integrated projectile launcher with 4 spinning blades (to a maximum of 10) and 2 smoke bombs (to a maximum of 5)."

  - name: "Smoke Bomb Launcher"
    desc: "`pf2:1` (manipulate) The clockwork assassin launches a smoke bomb. A screen of thick, opaque smoke fills a 10-foot burst within 60 feet of the clockwork assassin. Creatures within the area are concealed, and all other creatures are concealed to them. The smoke lasts for 1 minute or until dispersed by a strong wind."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The clockwork assassin's Strikes deal an additional 3d6+4 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Unbalancing Blow"
    desc: "  Creatures hit by the clockwork assassin's rapier hand Strike are [[Conditions/Off-Guard|Off-Guard]] until the start of the clockwork assassin's next turn."
 
```

```encounter-table
name: Clockwork Injector
creatures:
  - 1: Clockwork Injector
```




