---
title: "Meladaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gW2V3JJI9yWom1T8" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Meladaemon"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Meladaemon"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Lifesense (Imprecise) 30 Feet"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +20, Deception: +23, Intimidation: +23, Religion: +20, Stealth: +23, Survival: +19"
abilityMods: [7, 5, 6, 3, 4, 6]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +20, __Will__ +19; +1 status to all saves vs. magic"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  death effects; __Weaknesses__ holy 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense (Imprecise) 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Consumptive Aura"
    desc: " (aura,divine) 20 feet. A meladaemon emanates an aura of intense hunger. Each round a creature begins its turn in the aura, it must attempt a DC 27 Fortitude check save. On a failure, the creature takes 1d6 void damage (2d6 void damage on a critical failure) and becomes [[Conditions/Fatigued|Fatigued]]. This fatigue ends as soon as the creature eats any food."

  - name: "Withering Opportunity"
    desc: "`pf2:r`  **Trigger** The meladaemon is attacked by an adjacent creature and the attack misses\n* * *\n\n**Effect** The meladaemon swipes at the triggering creature, which must immediately attempt a save against the meladaemon's withering touch."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+24 (magical, reach 10 feet, unholy)\n__Damage__  2d12 + 13 piercing plus daemonic-famine 1d6 spirit plus daemonic-famine"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d8 + 13 slashing plus grab,withering-touch 1d6 spirit plus grab,withering-touch"

  - name: "Divine Innate Spells"
    desc: "DC 31, attack +21; __6th __  _[[Spells/Phantom Pain|Phantom Pain]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Force Barrage|Magic Missile (At will)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Good only)]]_"

  - name: "Rituals"
    desc: "_Blight_"

  - name: "Daemonic Famine"
    desc: " (disease) **Saving Throw** DC 29 Fortitude check\n\n**Stage 1** carrier (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)\n\n**Stage 4** as stage 3 (1 day)\n\n**Stage 5** [[Conditions/Enfeebled|Enfeebled 3]] (1 day)\n\n**Stage 6** dead"

  - name: "Withering Touch"
    desc: " (divine) When the meladaemon hits with a claw Strike or a creature begins its turn grabbed by the meladaemon, the creature must attempt a DC 30 Fortitude check save. On a failure, the creature takes 1d6 void damage and becomes [[Conditions/Fatigued|Fatigued]]. This fatigue ends when the creature drinks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Meladaemon
creatures:
  - 1: Meladaemon
```



Meladaemons personify death by starvation and thirst, and revel in spreading the same despair that brought about their mortal demise. When they aren't blighting fields, massacring livestock, or tainting water supplies, they experiment on prisoners to study how long creatures can go without sustenance and the deleterious effects that result from such deprivation. Fiercely loyal to Trelmarixian, Horseman of Famine, they serve no other beings. They work alongside other daemons if Trelmarixian wills it, but are notoriously traitorous.
