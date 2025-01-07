---
title: "Otyugh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.GR2KuAuRhtuFfaNG" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Otyugh"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Otyugh"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +14, Stealth: +8"
abilityMods: [6, 2, 4, -2, 2, -2]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +12, __Ref__ +8, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70; __Immunities__  disease"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Stench"
    desc: " (aura,olfactory) 40 feet. A creature entering the aura must succeed at a DC 20 Fortitude check save or be [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for the same duration on a critical failure). On a success, the creature is temporarily immune to the sickened and slowed effects of this stench for 1 hour. Regardless of the save, while within the aura, creatures take a -2 circumstance penalty to saves against diseases. An otyugh's stench is due to the offal and refuse that it wallows in, so cleaning the creature thoroughly (with [[Spells/Create Water|Create Water]] and sufficient scrubbing, for example) deactivates the aura, while a sufficiently plugged nose allows an individual to avoid exposure to the stench.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d6 + 6 piercing plus filth-fever"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+14 (agile, reach 10 feet)\n__Damage__  1d6 + 6 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6+6 bludgeoning, DC 22 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Filth Fever"
    desc: " (disease) The [[Conditions/Sickened|Sickened]] and [[Conditions/Unconscious|Unconscious]] conditions from filth fever don't improve on their own until the disease is cured.\n\n**Saving Throw** DC 20 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1d4 hours)\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** sickened 1 and [[Conditions/Slowed|Slowed 1]] as long as it remains sickened (1 day)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 5** dead"

  - name: "Reposition"
    desc: "`pf2:1`  The otyugh attempts to move all creatures that it has [[Conditions/Grabbed|Grabbed]] into other spaces within the reach of its tentacles, rolling a single Athletics check check and comparing the result against each creature's Fortitude DC. On a failure, the creature remains in place, and on a critical failure, the creature is no longer grabbed."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Otyugh
creatures:
  - 1: Otyugh
```



Lords of sewers, ditches, and landfllls, otyughs are filthy monstrosities that stomp about on three massive legs in search of tasty garbage and refuse. Using two barbed tentacles to grasp and tear, guided by a third with a proliferation of eyes at the end, the otyugh has perfectly adapted to life in its cramped, disgusting environment, where it uses its appendages to see into tight spaces and grasp hidden prey.

Most assume that otyughs originally evolved in swamps and moved into sewers as civilization encroached on their natural habitats. True or not, they are now one of the larger predators in those dank environs. Otyughs are territorial, but they have been known to form loose collectives, even giving each other important-sounding titles like 'king of offal'; and 'duchess of slime' to indicate their rank and station in their sludgy underworld beneath the streets.

Those who run across an otyugh might be surprised to hear it speak, shouting at intruders to leave its putrid home or demanding tribute in the form of trash or other prizes of dubious nature.
