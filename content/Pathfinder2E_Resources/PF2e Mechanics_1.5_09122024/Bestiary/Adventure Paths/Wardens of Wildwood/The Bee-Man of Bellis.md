---
title: "The Bee-Man of Bellis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pgQu0WEhDlOMDkX4" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "The Bee-Man of Bellis"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "The Bee-Man of Bellis"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[animal]]
trait_03: [[swarm]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; "
languages: "Common, Wildsong; speak with animals (insects only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Intimidation: +20, Stealth: +20, Survival: +12"
abilityMods: [3, 7, 6, 4, 4, 6]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +15, __Ref__ +21, __Will__ +18"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Immunities__  disease,  paralyzed,  precision,  sleep,  stunned,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 10, splash damage 10; __Resistances__ bludgeoning 10, piercing 10, slashing 5"
abilities_top:
  - name: ""

  - name: "Apian Emissaries"
    desc: "  The Bee-Man can use bees to duplicate the effects of [[Spells/Clairvoyance|Clairvoyance]] or [[Spells/Message|Message]] at will, with a maximum range of 13 miles. A successful DC 20 Perception check check identifies the presence of the bees acting as the sensors for these spells, but a DC 24 Nature check (expert) check is required to realize they are behaving under outside influence."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Smoke Susceptibility"
    desc: "  The Bee-Man is [[Conditions/Slowed|Slowed 1]] for 1 round if he starts his turn in heavy smoke."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Slam"
    desc: "+19 ()\n__Damage__  2d6 + 9 piercing plus apitoxin"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __5th __  _[[Spells/Summon Animal|Summon Animal (Bee Swarms Only, Treat as Wasp Swarms) (x3)]]_; __4th __  _[[Spells/Honeyed Words|Honeyed Words (x3)]]_; __2nd __  _[[Spells/Augury|Augury (At Will)]]_, _[[Spells/Speak with Animals|Speak with Animals (Constant, Insects Only)]]_; __1st __  _[[Spells/Illusory Disguise|Illusory Disguise (At Will, Male Human Only)]]_"

  - name: "Rituals"
    desc: "_Commune_, _Geas_, _Reincarnate_"

  - name: "Apitoxin"
    desc: " (poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage, [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and enfeebled 1 (1 round)\n\n**Stage 3** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "Evasive Swarm"
    desc: "  **Trigger** The Bee-Man moves at least 5 feet\n* * *\n\n**Effect** The Bee-Man gains [[Conditions/Concealed|Concealment]] against ranged attacks until the start of his next turn or until he makes an attack action, whichever comes first."

  - name: "Taboo Name"
    desc: "  Whenever the Bee-Man's full name (Vernon Vestha) is spoken aloud by a creature within 13 miles, he hears it and immediately knows the speaker's direction and distance from him."
 
```

```encounter-table
name: The Bee-Man of Bellis
creatures:
  - 1: The Bee-Man of Bellis
```


Male swarm of bees

According to legend, the forest hermit Vernon Vestha was once little more than a simple beekeeper, tending to his hives somewhere among the forests and townships of northeastern Andoran. Precisely how he started down the sinister path that made him what he is today remains unknown, but it is generally understood that Vernon came to a strange revelation one day: he saw in his bees the ability to divine the future beyond that of any mortal magic and became convinced that if only he could teach himself to hear the messages in their buzzing and interpret the patterns in their swarms, that power could be his as well. His curiosity became an obsession, and obsession quickly spiraled into madness, culminating in the fateful day that he sacrificed his humanity in some inscrutable honeyed rite to become fully one with his beloved bees.

To this day, they say, the Bee-Man still haunts the woods outside Bellis, waiting for someone to call him by speaking his name aloud. He often appears to those who seek his aid, although he seldom if ever grants it without exacting some terrible price in return.

## Swarm Dispersion

If the Bee-Man is reduced to 0 Hit Points, his physical body dissolves into a cloud of live bees, which immediately scatter in all directions. Legends vary on the length of time that must pass before the Bee-Man can return, as well as on whether it's possible to permanently destroy him by killing every one of the bees before they can escape.
