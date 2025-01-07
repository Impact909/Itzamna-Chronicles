---
title: "Clockwork Brewer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.maXm5HGfpUPwzmJg" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Clockwork Brewer"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Clockwork Brewer"
level: "Creature 3"
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
    desc: "Athletics: +9, Brewing Lore: +8"
abilityMods: [4, 3, 1, -5, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +10, __Will__ +8"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 3, orichalcum 3; __Resistances__ physical 3 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Artisan's Toolkit|Artisan's Tools (Brewing)]]"
  - name: "Mini-Keg"
    desc: "  A clockwork brewer can hold up to 5 gallons of liquid in a built-in tank. By default, this tank contains the clockwork brewer's beer."

  - name: "Standard Greeting"
    desc: "  Clockwork brewers have a limited set of pre-recorded phrases they can use to interact with clientele, based on their instructions. The audio is recorded on an embedded gemstone worth 5 gp. Removing a gemstone from or installing a gemstone into a clockwork brewer requires a successful DC 18 Thievery check check to Disable a Device; on a failure, the gemstone is undamaged, but any recorded sounds are erased."

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 18 Thievery check check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Leg"
    desc: "+9 (agile, unarmed)\n__Damage__  2d4 + 4 bludgeoning plus grab"

  - name: "Bottoms Up"
    desc: "`pf2:1`  **Requirements** The clockwork brewer has a creature [[Conditions/Grabbed|grappled]]\n* * *\n\n**Effect** The clockwork brewer force- feeds the grappled creature 1 serving of whatever liquid is in the clockwork brewer's tank (typically beer such as Smokeside Sour). The creature is exposed to the liquid's effects, and it can't breathe or speak until the start of its turn."

  - name: "Pre-Programmed Greeting"
    desc: "`pf2:1` (auditory,mental) The clockwork brewer clearly delivers a disarmingly friendly greeting to a creature within 30 feet. The creature attempts a DC 17 Will check save. On a failure, the creature is [[Conditions/Off-Guard|Off-Guard]] against the clockwork brewer's next attack before the end of the brewer's next turn. The target is then immune to Pre-Programmed Greeting for 1 day."

  - name: "Smokeside Sour"
    desc: " (ingested,poison) **Saving Throw** DC 12 Fortitude check\n\n**Maximum Duration** 1 hour\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] (10 minutes)\n\n**Stage 2** clumsy 1 and [[Conditions/Stupefied|Stupefied 1]] (10 minutes)\n\n**Stage 3** [[Conditions/Clumsy|Clumsy 2]], [[Conditions/Stupefied|Stupefied 2]], and sickened (40 minutes)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Clockwork Brewer
creatures:
  - 1: Clockwork Brewer
```



Clockwork creatures are as common in Alkenstar as carts and horses are in most Inner Sea region cities. In the City of Smog, clockworks perform many of the simple, repetitive tasks that sentient workers find boring, as well as dangerous jobs such as private security or riot control.

With the rise of the automated workforce in Alkenstar came the "professional" line of clockworks, capable of carrying out more complex tasks and even interacting with the public. These clockworks were given modules inscribed with information and procedures for carrying out a specific profession. The clockwork brewer is one such example, capable of extracting wort, stirring a fermenter, or monitoring a boiling temperature. As many other types of clockwork professional exist as there are professions; clockworks have been programmed to reshelf library books, swab ship decks, and fill holes in heavily trafficked roads.

Clockwork professionals made by reputable manufacturers are generally considered safe to interact with the public. Accidents have been known to occur, however, particularly when careless engineers fail to perform regular maintenance checks or when operators program a clockwork with insufficiently specific directives. Flesh and blood laborers forced to work in close proximity to a clockwork professional tend to keep a wide berth.
