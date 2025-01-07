---
title: "Slithering Pit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q0azOvR1WQw0Fq35" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Slithering Pit"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Slithering Pit"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +10"
abilityMods: [7, -5, 7, -5, 0, -5]
speed: 10 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 14
armorclass:
  - name: AC
    desc: "14 (10 from inside the Dimensional Pit); __Fort__ +18, __Ref__ +6, __Will__ +11"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Transparent"
    desc: "  A slithering pit is so clear it's difficult to spot. A successful DC 30 Perception check check is required to notice a stationary slithering pit, and a creature must be [[Actions/Search|Searching]] to attempt this check.\n\nA creature that walks into the pit's space might fall into any pit currently in effect due to Dimensional Pit."

abilities_mid:
  - name: ""
  - name: "Breach Vulnerability"
    desc: "  Ingesting an extradimensional space like that found in a _bag of holding_ deals 6d8 force damage to the slithering pit and its occupants. The slithering pit then immediately uses Out You Go."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+18 (reach 10 feet)\n__Damage__  2d8 + 9 bludgeoning plus improved-grab"

  - name: "Dimensional Pit"
    desc: "`pf2:2` (extradimensional,occult) The slithering pit opens an extradimensional, 20-foot-deep pit that covers its own space and all adjacent squares unless they're walls or similar blocking terrain.\n\nAny other creature occupying or entering pit spaces must succeed at a DC 22 Reflex check save or fall into the pit, taking damage from the fall (typically 10 bludgeoning damage). Any creature [[Conditions/Grabbed|Grabbed]] by the ooze falls in and is no longer grabbed, even if it was outside the pit squares.\n\nWhile a dimensional pit is open, the slithering pit is [[Conditions/Immobilized|Immobilized]], can't be forced to move, and can make pseudopod Strikes originating from the walls of the pit. A creature that starts its turn at the bottom of the pit takes 2d6 acid damage. [[Actions/Climb|Climbing]] the walls of the pit requires a DC 22 Athletics check check.\n\nWhen the slithering pit dies, the dimensional pit closes and creatures inside are ejected, with the effects of Out You Go."

  - name: "Flurry of Pods"
    desc: "`pf2:2`  The slithering pit makes a single pseudopod Strike against each target within range it doesn't already have [[Conditions/Grabbed|Grabbed]]. These attacks count toward the slithering pit's multiple attack penalty, but the penalty doesn't increase until after all of these attacks."

  - name: "Out You Go"
    desc: "`pf2:1`  The slithering pit closes all pit spaces it created using Dimensional Pit, ejecting all its occupants onto the ground into random free spaces where the pit opened. Each occupant takes 4d6 bludgeoning damage (DC 22 Reflex check save)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Slithering Pit
creatures:
  - 1: Slithering Pit
```



A slithering pit is a strange, nearly invisible ooze with an extradimensional space for its digestive system, which mimics the appearance of an acid-filled stone pit. It slowly dissolves its captives in stomach acid until they can be digested. A slithering pit can go weeks without feeding, affording it patience.

Thriving in dilapidated areas, slithering pits take up positions among the plentiful potholes where they can easily pass for just another blemish. They crawl across ramshackle cobblestone streets and damp underground complexes, waiting for unwary prey to stumble by and fall in.
