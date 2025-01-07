---
title: "Brughadatch"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WkTVDbcZY3yBfnhq" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Brughadatch"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Brughadatch"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[fey]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Deception: +22, Intimidation: +22, Nature: +22, Survival: +20"
abilityMods: [5, 3, 4, 0, 4, 6]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +16, __Will__ +20"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 ()\n__Damage__  2d10 + 9 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile)\n__Damage__  2d8 + 5 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 28, attack +22; __4th __  _[[Spells/Charm|Charm (At-Will)]]_, _[[Spells/Confusion|Confusion]]_; __3rd __  _[[Spells/Enthrall|Enthrall (x3)]]_; __2nd __  _[[Spells/Faerie Fire|Faerie Fire]]_, _[[Spells/Laughing Fit|Hideous Laughter]]_; __1st __  _[[Spells/Fear|Fear (At-Will)]]_\n__Cantrips__  __(4th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Produce Flame|Produce Flame]]_"

  - name: "Deceitful Feast"
    desc: " (illusion) The brughadatch conjures a decadent, enticing feast void of nutritional substance. This conjuration takes 1 minute and lasts for 24 hours. For each item of illusory food a creature eats, it must attempt a DC 29 Will check save.\n* * *\n\n**Critical Success** The creature sees through the illusion and becomes immune to the effects of Deceitful Feast for 24 hours.\n\n**Success** The creature doesn't see through the illusion but is unaffected by the food.\n\n**Failure** The creature takes a -1 circumstance penalty to Will saves against any of the brughadatch's spells or abilities. The penalty increases with each failed save, to a maximum of -5.\n\n**Critical Failure** As failure, plus for 1 hour, the creature's attitude becomes helpful to the brughadatch, and the creature can't use hostile actions against them.\n\n[[Bestiary Effects/Effect_ Deceitful Feast (Failure)|Effect: Deceitful Feast (Failure)]]"

  - name: "Psychic Sip"
    desc: "`pf2:1`  **Requirements** Targets must have critically failed a save against a brughadatch's Deceitful Feast or charm innate spell\n\n**Frequency** once per round\n* * *\n\n**Effect** The brughadatch feasts on the souls of the creatures they've tricked. They target up to five creatures within 30 feet and feast on their ambient brainpower, dealing 4d10 mental damage (DC 26 Will check save) to each creature. Unless a target succeeds at the Will save, this damage does not end the [[Spells/Charm|Charm]] effect or the effect of Deceitful Feast as a hostile action normally would."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Brughadatch
creatures:
  - 1: Brughadatch
```



The biggest difference between a gahlepod and a grown brughadatch isn't their humanoid appearance, but the powerful magic they gain as they mature.

* * *

Brughadatches are malevolent fey tricksters with distinct stages of life: they spawn from the First World's primal energies as esurient tadpoles, grow into humanoids capable of creating enticing illusions, then finally evolve into huge, slothful toads that warp their environs with mere thoughts.
