---
title: "Harpy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8PrVCjbUWGSZEuDb" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/beast
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Harpy"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Harpy"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[beast]]
trait_03: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common; Wind&#x27;s Whispers"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Deception: +11, Intimidation: +13, Performance: +11, Stealth: +11, Thievery: +13"
abilityMods: [1, 4, 0, -1, 1, 2]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +9, __Ref__ +15, __Will__ +12"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""

  - name: "Wind's Whispers"
    desc: " (air,primal) When a harpy speaks, they can choose one creature within 90 feet. That creature can hear the harpy's words over any other sound, but no other creature hears the words at all."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 30 feet, DC 21 Fortitude check\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Talon"
    desc: "+15 (agile, finesse)\n__Damage__  2d6 + 4 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (finesse)\n__Damage__  2d8 + 4 piercing plus putrid-plague"

  - name: "Hungry Winds"
    desc: "`pf2:2` (air,concentrate,primal) The harpy uses the wind to pull its prey closer. A target within 20 feet must succeed at a DC 21 Fortitude check save or be pulled adjacent to the harpy, where they make a jaws Strike against the target. If the target was pulled off the ground and can't fly, it then falls as normal."

  - name: "Putrid Plague"
    desc: " (disease) The sickened and unconscious conditions from putrid plague can't end or be reduced until the disease is cured\n\n**Saving Throw** DC 19 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1d4 hours),\n\n**Stage 2** [[Conditions/Sickened|Sickened 1]] (1 day),\n\n**Stage 3** sickened 1 and [[Conditions/Slowed|Slowed 1]] (1 day),\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day),\n\n**Stage 5** dead"
 
```

```encounter-table
name: Harpy
creatures:
  - 1: Harpy
```



Harpies are amalgamations of human and bird, resembling feral humans with wings, talons, and sharp teeth. They use their ancestral control of the wind to lure prey or even directly pull in their next meal. They enjoy causing confusion and fear in their prey before they strike, believing it creates a savory flavor in the flesh. Harpies can eat most creatures but strongly prefer sapient prey—humans and elves in particular. Although harpies will eat goblins if sufficiently hungry, they dislike their flavor and avoid eating them if possible. This doesn't comfort goblins, of course, who have a particularly strong fear of harpies.

Because their aeries often reek with the gore of their kills and careless spatters of guano, harpies carry a distinctly vile scent that canny travelers associate with danger. Harpies who roost close to civilization make better efforts to keep clean, though these efforts have mixed results.

Somewhere among the filth, most aeries have a shrine dedicated to the demon lord Pazuzu. Harpy legends credit him with raising them up from simple air spirits to their current station, and their gratitude typically takes the shape of a sketched figure in a corner piled with offerings. More devout families build portable wooden shrines that are carried from aerie to aerie for generations.

Harpies live in family groups or larger clans. Most adults stand 5 feet tall and weigh around 90 pounds. While some use relatively simple weapons, those who master the use of the bow are regarded as heroes among their kind.
