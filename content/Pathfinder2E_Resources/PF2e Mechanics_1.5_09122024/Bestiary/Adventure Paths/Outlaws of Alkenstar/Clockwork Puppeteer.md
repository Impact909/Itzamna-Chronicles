---
title: "Clockwork Puppeteer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5oLOUuICbtswn2vX" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Clockwork Puppeteer"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Clockwork Puppeteer"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +0, Stealth: +25"
abilityMods: [6, 6, 2, -5, 2, -5]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +22, __Ref__ +25, __Will__ +19"
hp: 205
health:
  - name: ""
  - name: HP
    desc: "205; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 10, orichalcum 10; __Resistances__ physical 10 (except adamantine or orichalcum)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 22 Thievery check, standby\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "Clockwork Swarm"
    desc: " (aura) 30 feet. A cloud of flying, spiderlike clockworks surrounds the clockwork puppeteer. A creature that ends its turn in the cloud takes 4d8 piercing damage (DC 29 Reflex check)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 ()\n__Damage__  3d10 + 9 slashing"

  - name: "**Ranged** `pf2:1` String"
    desc: "+24 (range 60 feet)\n__Damage__  3d8 + 9 slashing plus clockwork-string"

  - name: "Clockwork String"
    desc: "  Any creature hit by the puppeteer's string is [[Conditions/Grabbed|Grabbed]]. The puppeteer can move while it has a creature grabbed with its string, but it automatically releases the creature if the puppeteer moves beyond the string's 60-foot length. The puppeteer can use up to six strings at a time. It can release any creature grabbed by a string as a free action. Each string has AC 30, and its [[Actions/Escape|Escape]] DC is 32. A string can be severed by a Strike that deals at least 20 slashing damage to it. This doesn't deal any damage to the clockwork puppeteer."

  - name: "Create Puppet"
    desc: "`pf2:r` (arcane) **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the puppeteer's clockwork string dies\n* * *\n\n**Effect** The triggering creature's body becomes infested with tiny clockworks. This puppet is fully under the clockwork puppeteer's control and has statistics identical to a zombie of its size with the following exceptions: It loses the undead trait, loses void healing, loses its weakness to vitality damage, and gains the construct trait."

  - name: "Pull String"
    desc: "`pf2:1`  The puppeteer reins in a creature [[Conditions/Grabbed|Grabbed]] by its string. The puppeteer attempts an Athletics check check against the creature's Fortitude DC. On a success, the puppeteer pulls the creature 15 feet closer to it (30 feet closer on a critical success)."
 
```

```encounter-table
name: Clockwork Puppeteer
creatures:
  - 1: Clockwork Puppeteer
```



Clockwork puppeteers are grim constructs capable of controlling corpses like puppets. They typically stand 12 feet tall and have spindly legs and long arms ending with scalpel-like claws. Dozens of metallic strings, composed of interlocking clockwork links, hang from their wrists.

* * *

As one delves deeper into the industrial heart of Alkenstar, the clockwork adversaries one faces become ever more complex and deadly.
