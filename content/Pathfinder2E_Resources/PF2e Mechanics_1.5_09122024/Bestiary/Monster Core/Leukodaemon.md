---
title: "Leukodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.niipbIPS3tOSu7zx" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Leukodaemon"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Leukodaemon"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Daemonic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Intimidation: +18, Medicine: +20, Religion: +20, Stealth: +18, Survival: +16"
abilityMods: [6, 5, 1, 3, 5, 3]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +15, __Ref__ +21, __Will__ +19; +1 status to all saves vs. magic"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Immunities__  death effects,  disease; __Weaknesses__ holy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|+1 Striking Composite Longbow]], 50x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Plaguesense (Imprecise) 60 feet"
    desc: "  A leukodaemon senses any creature with a disease, and they know the type and current stage of all diseases carried by any creature within range."

abilities_mid:
  - name: ""
  - name: "Infectious Aura"
    desc: " (aura,disease) 30 feet.\n\nLeukodaemons radiate infection. All creatures within 30 feet of a leukodaemon take a –2 status penalty to saves against disease. If a creature within range contracts or progresses a disease, all adjacent creatures are exposed to the same disease, at the same DC.\n\n[[Bestiary Effects/Effect_ Infectious Aura|Effect: Infectious Aura]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (disease, magical, reach 10 feet, unholy)\n__Damage__  2d12 + 9 piercing plus daemonic-pestilence"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, disease, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 9 slashing plus daemonic-pestilence"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+21 (deadly d10, disease, magical, propulsive, range increment 100 feet, reload 0, unholy, volley 30 ft.)\n__Damage__  2d8 + 9 piercing plus daemonic-pestilence"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Dispel Magic|Dispel Magic (x2)]]_, _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Daemonic Pestilence"
    desc: " (disease) The leukodaemon can telepathically communicate with the afflicted creature at any distance on the same plane\n\n**Saving Throw** DC 28 Fortitude check\n* * *\n\n**Stage 1** carrier (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] (1 day)\n\n**Stage 4** drained 2 (1 day)\n\n**Stage 5** [[Conditions/Drained|Drained 3]] (1 week)\n\n**Stage 6** dead"

  - name: "Plague Breath"
    desc: "`pf2:2` (divine,unholy) The leukodaemon exhales a cloud of corpse-bloated, biting black flies in a 20-foot cone. Creatures within the cone take 4d8 piercing damage (DC 28 Reflex check save). A creature that fails the save becomes [[Conditions/Sickened|Sickened 1]] (or [[Conditions/Sickened|Sickened 2]] on a critical failure)."

  - name: "Quicken Pestilence"
    desc: "`pf2:1` (divine,manipulate) The leukodaemon coaxes a disease into full bloom. They choose a target in their aura of pestilence that's currently affected by a disease. That creature must attempt a Fortitude save against the disease as if the interval for the disease's current stage had passed."
 
```

```encounter-table
name: Leukodaemon
creatures:
  - 1: Leukodaemon
```



These skull-headed, vulture-winged daemons are harbingers of pestilence and servants of their patron Apocalypse Rider, Apollyon. Manifestations of evil souls who perished from disease in life, leukodaemons work tirelessly alongside one another to spread disease across all the worlds of the multiverse.

* * *

Denizens of the bleak and terrible plane of Abaddon, daemons are shaped by and devoted to the destruction of life in all its forms. They seek the death of every mortal being by the most painful and horrible means possible, in service to the Apocalypse Riders. Each kind of daemon represents a different way to die, and their powers are nearly always aimed at spreading that particular form of death. Through the use of these powers, they seek to drag all existence down into a pit of hopelessness and despair, and to commit all souls to oblivion.

While mortals who summon daemons usually seek to use the creatures' destructive and corrupting powers for their own ends, daemons always look for ways to spread fear, doubt, and despair wherever they go. Often, daemons disguise their plots as the workings of other fiends, knowing that such confusion compounds mortals' fear and keeps those mortals from bringing the most effective weapons. As a result, learned mortals sometimes refer to daemons as "riders" after their leaders or "soul mongers" after their largest industry.

While many fiends seek to tempt mortals into lives of nihilistic evil to increase their own numbers and power on their native planes, daemons are further driven by a supernatural hunger for mortal souls and use a variety of methods—not least of which is the cacodaemons' soul gems—to entrap them. On Abaddon and in other forbidding places across the multiverse, souls are simultaneously a delicacy, a trade good, and a source of magical power, and the daemons are among the greatest gluttons, merchants, and abusers of this spiritual "resource."
