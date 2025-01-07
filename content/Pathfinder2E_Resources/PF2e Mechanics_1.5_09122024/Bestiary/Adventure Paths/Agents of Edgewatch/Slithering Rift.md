---
title: "Slithering Rift"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.noz2VWAdqPIO2WrD" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Slithering Rift"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Slithering Rift"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Tremorsense (Imprecise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +35, Stealth: +38"
abilityMods: [9, -2, 7, -5, 0, -5]
speed: 20 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 31
armorclass:
  - name: AC
    desc: "31 (27 from inside the Dimensional Pit); __Fort__ +33, __Ref__ +20, __Will__ +26"
hp: 535
health:
  - name: ""
  - name: HP
    desc: "535; __Immunities__  unconscious,  acid,  piercing,  precision,  critical hits,  visual,  mental; __Resistances__ bludgeoning 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Transparent"
    desc: "  A slithering rift is so clear that it's difficult to spot. A successful DC 48 Perception check check is required to notice a stationary slithering rift, and a creature must be [[Actions/Search|Searching]] to attempt this check.\n\nA creature that walks into the rift's space might fall into any pit currently in effect due to Dimensional Pit."

abilities_mid:
  - name: ""
  - name: "Breach Vulnerability"
    desc: "  Ingesting an extradimensional space like that found in a _bag of holding_ deals 12d8 force damage to the slithering rift and its occupants.\n\nThe slithering rift then immediately uses Out You Go."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+35 (magical, reach 15 feet)\n__Damage__  4d10 + 18 piercing plus improved-grab"

  - name: "Dimensional Pit"
    desc: "`pf2:2` (extradimensional) The slithering rift opens an extradimensional, 20-foot-deep pit that covers its own space and all adjacent squares unless they are walls or similarly blocking terrain.\n\nAny other creature occupying spaces in the pit must succeed at a DC 40 Reflex check save or fall into the pit, taking damage from the fall (typically 10 bludgeoning damage). Any creature grabbed by the ooze is released from the [[Bestiary Ability Glossary/Improved Grab|Grab]] and falls in, even if it was outside the pit squares.\n\nWhile the pit is open, the slithering rift is [[Conditions/Immobilized|Immobilized]] and can't be forced to move. It can make pseudopod Strikes originating from the walls of the pit. A creature that starts its turn at the bottom of the pit takes 5d6 acid damage.\n\nCreatures can climb the walls with a DC 40 Athletics check check. When the slithering rift dies, the pit closes and creatures inside are ejected, as Out you Go."

  - name: "Flurry of Pods"
    desc: "`pf2:2`  The slithering rift makes a single pseudopod Strike against each target within range it hasn't already [[Conditions/Grabbed|Grabbed]].\n\nThese attacks count toward the slithering rift's multiple attack penalty, but this penalty doesn't increase until after all of these attacks."

  - name: "Out You Go"
    desc: "`pf2:1`  The slithering rift closes all pit spaces it created using Dimensional Pit, ejecting all its occupants onto the ground into random free spaces where the opening of the pit was.\n\nEach occupant takes 9d6 bludgeoning damage (DC 40 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Slithering Rift
creatures:
  - 1: Slithering Rift
```




