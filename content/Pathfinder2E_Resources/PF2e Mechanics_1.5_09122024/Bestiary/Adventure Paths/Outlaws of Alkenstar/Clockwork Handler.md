---
title: "Clockwork Handler"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tRkosJoS3RZAvTU8" 
tags:
  - pf2e/creature/type/clockwork
  - pf2e/creature/type/construct
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Clockwork Handler"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #178: Punks in a Powder Keg"
name: "Clockwork Handler"
level: "Creature 1"
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
    desc: "Athletics: +7"
abilityMods: [4, 2, 3, -5, 3, -5]
speed: 25 feet
sourcebook: "_Pathfinder #178: Punks in a Powder Keg_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +7, __Will__ +6"
hp: 16
health:
  - name: ""
  - name: HP
    desc: "16; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental; __Weaknesses__ electricity 2, orichalcum 2; __Resistances__ physical 2 (except adamantine or orichalcum)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x [[Equipment/Javelin|Javelin]], [[Equipment/Everlight Crystal|Everburning Torch]], [[Equipment/Rope|Rope]]"
  - name: "Spotlight"
    desc: "  The clockwork handler can use the _[[Equipment/Everlight Crystal|Everburning Torch]]_ built into its helmet to illuminate areas it's examining. Whenever it Seeks in a 30-foot cone and rolls a successful Perception check, the clockwork handler gets a critical success instead."

  - name: "[[Creature Family Ability Glossary/(Clockwork Creature) Wind-Up|Wind-Up]]"
    desc: "  24 hours, DC 15 Thievery check check, standby\n* * *\n\nFor a clockwork to act, it must be wound with a unique key by another creature. This takes 1 minute. Once wound, it remains operational for the listed amount of time, usually 24 hours, after which time it becomes unaware of its surroundings and can't act until it's wound again. Some clockworks' abilities require them to spend some of their remaining operational time. They can't spend more than they have and shut down immediately once they have 0 time remaining. If it's unclear when a clockwork was last wound, most clockwork keepers wind all their clockworks at a set time, typically 8 a.m.\n\nA clockwork that lists standby in its wind-up entry can enter standby mode as a 3-action activity. Its operational time doesn't decrease in standby, but it can sense its surroundings (with a -2 penalty to Perception). It can't act, with one exception: when it perceives a creature, it can exit standby as a reaction (rolling initiative if appropriate).\n\nA creature can attempt to Disable a Device to wind a clockwork down (with a DC listed in the wind-up entry). For each success, the clockwork loses 1 hour of operational time. This can be done even if the clockwork is in standby mode."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, nonlethal, unarmed)\n__Damage__  1d4 + 4 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+5 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "Hog-tie"
    desc: "`pf2:2`  **Requirements** The clockwork handler has a creature [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The clockwork handler cuts a length of rope from the supply in its chassis to tie up the restrained creature. The creature is restrained until it Escapes or Forces Open the rope with a successful DC 15 check (typically an attack roll or Thievery check to [[Actions/Escape|Escape]], or an Athletics check to [[Actions/Force Open|Force Open]] the ropes; restrained creatures don't take a -2 penalty on this check for not using a crowbar). The rope has Hardness 2 and 8 Hit Points (BT 4)."

  - name: "Siren"
    desc: "`pf2:2`  The clockwork handler emits a loud noise (such as a bell or high- pitched mechanical scream) that can be easily heard by anyone within 500 feet. Creatures within 100 feet take a -2 circumstance penalty to Perception checks that are hearing-based. Creatures within 30 feet who fail a DC 14 Fortitude check save can't hear anything but the siren, critically fail Perception checks that require hearing, and are immune to auditory effects. This effect lasts until the creature leaves the area and for 1 round afterward."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Clockwork Handler
creatures:
  - 1: Clockwork Handler
```



Clockwork creatures are as common in Alkenstar as carts and horses are in most Inner Sea region cities. In the City of Smog, clockworks perform many of the simple, repetitive tasks that sentient workers find boring, as well as dangerous jobs such as private security or riot control.

One of the jobs most commonly outsourced to clockworks is guard duty. Clockwork soldiers are often too costly to employ en masse, so municipalities looking to cut corners devised the much-cheaper clockwork handler, a budget-friendly construct sufficient for rat catching, door watching, and basic patrol work.

Handlers are typically programmed to react efficiently to certain situations such as intruders or assailants. To that end, all handlers are equipped with an everburning torch fastened to their hooded lantern-like heads. Furthermore, most clockwork handlers used in public places have their fists covered in a padded material to ensure they don't accidentally beat suspects to death, though these modifications are removable (removing the nonlethal trait from their fist Strike). The nonlethal approach is considered the safest, as clockwork creatures don't always have the keenest judgement on who is a criminal and who is a customer. A healthy supply of rope allows the clockwork handler to quickly tie-up unruly vagabonds, that they might be brought to justice.
