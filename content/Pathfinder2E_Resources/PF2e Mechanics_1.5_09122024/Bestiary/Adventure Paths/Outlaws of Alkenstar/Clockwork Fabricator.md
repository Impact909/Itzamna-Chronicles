---
title: "Clockwork Fabricator"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.r3aJSp52kiXHZ2Ym" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Clockwork Fabricator"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Clockwork Fabricator"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[clockwork]]
trait_02: [[construct]]
trait_03: [[mindless]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12, Crafting: +9"
abilityMods: [6, 3, 2, -5, 3, -5]
speed: 25 feet
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +10, __Ref__ +11, __Will__ +9"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 4, orichalcum 4; __Resistances__ physical 4 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Artisan's Toolkit|Artisan's Tools]]"
  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 19 Thievery check check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Buzz-Saw Blade"
    desc: "+16 (forceful, sweep)\n__Damage__  1d4 + 6 slashing 1d6 bleed"

  - name: "**Melee** `pf2:1` Crushing Vise"
    desc: "+14 (grapple)\n__Damage__  2d6 + 6 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Sledgehammer"
    desc: "+12 ()\n__Damage__  2d10 + 6 bludgeoning"

  - name: "**Melee** `pf2:1` Pneumatic Chisel"
    desc: "+14 ()\n__Damage__  2d8 + 6 piercing"

  - name: "**Melee** `pf2:1` Arm"
    desc: "+14 (agile, unarmed)\n__Damage__  2d4 + 6 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Towing Anchor"
    desc: "+11 (thrown 30 ft.)\n__Damage__  1d4 + 6 piercing"

  - name: "**Ranged** `pf2:1` Nail Gun"
    desc: "+11 (agile, range 10 feet)\n__Damage__  2d8 piercing"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  **Requirements** The clockwork fabricator has a creature grappled or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** 2d4+4 bludgeoning, DC 21 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Modular Arms"
    desc: "  A clockwork fabricator is built to perform a specific type of task repeatedly, and it comes with built-in artisan's tools and two detachable \"arms.\" An adjacent creature can forcibly remove a clockwork fabricator's arm with a successful DC 18 Thievery check check to Disable a Device. A creature can Interact to install a new arm with a successful DC 18 Engineering check Lore check. A fabricator has two of any of the following types of arms.\n\n*   **Melee** `pf2:1` buzz-saw blade +16 (forceful, sweep), Damage 1d4+6 slashing plus 1d6 bleed\n*   **Melee** `pf2:1` crushing vise +14 (grapple), Damage 2d6+6 bludgeoning plus Grab\n*   **Melee** `pf2:1` sledgehammer +12, Damage 2d10+6 bludgeoning\n*   **Ranged** `pf2:1` nail gun +11 (agile, range 10 feet), Damage 2d8 piercing\n*   **Melee** `pf2:1` pneumatic chisel +14, Damage 2d8+6 piercing\n*   **Ranged** `pf2:1` towing anchor +11 (thrown 30 feet), Damage 1d4+6 piercing"

  - name: "Pull"
    desc: "`pf2:1`  **Requirements** The clockwork fabricator's last action was a successful towing anchor Strike\n* * *\n\n**Effect** The clockwork fabricator reels in the anchor and attempts an Athletics check check against the target's Fortitude DC. On a success, the clockwork fabricator pulls the target into a free square adjacent to it. This movement is forced movement."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Clockwork Fabricator
creatures:
  - 1: Clockwork Fabricator
```



Clockwork creatures are as common in Alkenstar as carts and horses are in most Inner Sea region cities. In the City of Smog, clockworks perform many of the simple, repetitive tasks that sentient workers find boring, as well as dangerous jobs such as private security or riot control.

A common sight among Alkenstar work crews, construction teams, and mining operations, the clockwork fabricator is a one-size-fits-all construction companion. These clockworks can be programmed to perform up to two simple, repetitive tasks such as hauling equipment, chopping down trees, or grinding up hunks of ore. The modular nature of these units makes them even more valuable-after finishing a day's work sawing planks, the same machine can be unwound, updated with a new modular arm or two, and then re-wound and given new instructions.

While it's possible to remove or replace an arm while a fabricator in use, doing so is dangerous and likely to void the manufacturer's warranty, to say nothing of the danger posed to the engineer doing the retrofitting.
