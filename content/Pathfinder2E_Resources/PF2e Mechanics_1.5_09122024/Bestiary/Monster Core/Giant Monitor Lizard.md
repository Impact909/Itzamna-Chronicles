---
title: "Giant Monitor Lizard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.G6lWRWQwi1YQ43eo" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Giant Monitor Lizard"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Monitor Lizard"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +9, Stealth: +6"
abilityMods: [3, 2, 3, -4, 1, -2]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +8, __Will__ +5"
hp: 36
health:
  - name: ""
  - name: HP
    desc: "36"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d10 + 3 piercing plus grab,monitor-lizard-venom"

  - name: "Gnashing Grip"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the giant monitor lizard's jaws fails a check to [[Actions/Escape|Escape]].\n* * *\n\n**Effect** The giant monitor lizard's jaws deal 1d6 piercing damage and the triggering creature is exposed to monitor lizard venom."

  - name: "Lurching Charge"
    desc: "`pf2:2`  The giant monitor lizard Strides twice and then makes a jaws Strike. If the lizard moved at least 20 feet away from its starting position, it gains a +2 circumstance bonus to this attack roll."

  - name: "Monitor Lizard Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Monitor Lizard
creatures:
  - 1: Giant Monitor Lizard
```



Large and seemingly ponderous, a monitor lizard is a deceptively swift and ruthless predator. It ambushes its prey by rushing out from cover and biting the target with its powerful jaws. A giant monitor lizard's saliva is venomous, allowing it to bring down prey larger than it can easily haul away in its jaws. Giant monitor lizards grow up to 14 feet long, including their long tails, and they weigh about 350 pounds. Their bodies are normally dark brown with patches of yellow or green.

When nesting, a giant monitor lizard digs a deep burrow to hide in. The burrow serves as both a safe haven and a location from which the lizard can ambush larger prey such as deer, boars, or even humanoids. A giant monitor lizard can consume nearly its own body weight in a single meal, and its loosely articulated jaws allow it to swallow surprisingly large prey.

* * *

Lizards have a wide range of appearances and abilities, but most share a basic reptilian shape—long tails, wide toothy mouths, and four legs. While a few species are capable of movement on two legs for short periods of time, most are strictly quadrupedal. The three species presented here represent the most common and well-known of the larger species.
