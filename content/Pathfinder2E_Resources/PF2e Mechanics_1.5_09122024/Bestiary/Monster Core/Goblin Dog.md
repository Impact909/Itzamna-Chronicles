---
title: "Goblin Dog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pR5WjYC9uF50Fu2F" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Goblin Dog"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Goblin Dog"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +7"
abilityMods: [3, 2, 2, -4, 1, -1]
speed: 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +8, __Will__ +5"
hp: 17
health:
  - name: ""
  - name: HP
    desc: "17"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 17 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

  - name: "Irritating Dander"
    desc: "  A creature that hits the goblin dog with an unarmed attack, tries to [[Actions/Grapple|Grapple]] it, or otherwise touches it is exposed to goblin pox."

  - name: "Juke"
    desc: "`pf2:r`  **Requirements** A creature must be mounted on the goblin dog.\n\n**Trigger** The rider issues a command to the goblin dog.\n* * *\n\n**Effect** The goblin dog Steps before following the command."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d6 + 3 piercing plus goblin-pox"

  - name: "Goblin Pox"
    desc: " (disease) Goblins and goblin dogs are immune to goblin pox.\n\n**Saving Throw** DC 17 Fortitude check\n* * *\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** sickened 1 and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 3** [[Conditions/Sickened|Sickened 2]] and can't reduce its sickened value below 1 (1 day)"

  - name: "Scratch"
    desc: "`pf2:2` (manipulate) The goblin dog vigorously scratches itself, exposing all adjacent creatures to goblin pox."
 
```

```encounter-table
name: Goblin Dog
creatures:
  - 1: Goblin Dog
```



Goblins' eponymous pets aren't true canines at all but rather large, blunt-nosed rodents with thin bodies and long legs. Often as cowardly as they are ugly, goblin dogs prefer to lurk behind bushes or in deep shadows, only pouncing upon lone or wounded prey. Goblin dogs frequently roam in packs, but they are likely to flee from a fight if injured, even if it means abandoning their packmates.

Goblin dogs take their name from a long association with goblins, who breed the beasts as guard animals and mounts. Most goblins take issue with the name, as the average goblin is appalled at the suggestion that their favored mounts have anything at all to do with actual dogs. Of course, being goblins, they haven't bothered to come up with their own unique name for the creatures.

Even the most pampered goblin dogs have itchy mange and prolific dander that tenaciously affects those who come in contact with them. This "goblin pox" causes itchy hives and festering sores that are as unsightly as they are irritating and distracting. Goblin dog dander causes allergic reactions in nearly all other creatures that don't share goblin dogs' terrible hygiene—with the notable exception being, of course, goblins, who remain entirely immune to the disease regardless of cleanliness.

Hunger can drive goblin dogs to bouts of uncharacteristic violence, and crueler goblins sometimes purposefully starve their pets on the eve of battle. Goblin dogs subsist on whatever organic material they can scavenge; they particularly enjoy fresh carrion. Although goblins are far from picky eaters themselves, they value goblin dogs because the noisome animals will consume material that even goblins won't touch. In fact, "Will It Eat?" is one of the most popular games goblins play with their pets, where a wide range of morsels (not always edible or safe to consume) are dangled before a goblin dog's snout. Sadly, the game "Will It Die?" is often played after "Will It Eat?" Goblin dogs that survive the second game earn renown for their digestive prowess and often become favored tribal pets, treated even better than most of the rank-and-file goblins.
