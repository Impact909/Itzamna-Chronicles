---
title: "Reef Octopus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6b4qO9lBi2xWvEUu" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Reef Octopus"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Reef Octopus"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +9"
abilityMods: [1, 4, 1, -4, 1, 0]
speed: 10 feet,  swim 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +6, __Ref__ +9, __Will__ +7"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Resistances__ cold 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+9 (finesse)\n__Damage__  1d10 + 1 piercing plus reef-octopus-venom"

  - name: "**Melee** `pf2:1` Arm"
    desc: "+9 (agile, finesse)\n__Damage__  1d6 + 1 bludgeoning plus grab"

  - name: "Camouflage"
    desc: "  The reef octopus can change the color of its skin to [[Actions/Hide|Hide]] even if it doesn't have cover."

  - name: "Ink Cloud"
    desc: "`pf2:1`  The reef octopus emits a cloud of dark-brown ink in a 10-foot emanation. This cloud has no effect outside of water. Creatures inside the cloud are [[Conditions/Hidden|Hidden]] and can't use their sense of smell. The cloud dissipates after 1 minute.\n\nThe octopus can't use Ink Cloud again for 2d6 rounds."

  - name: "Jet"
    desc: "`pf2:2`  The reef octopus moves up to 80 feet in a straight line through the water without triggering reactions."

  - name: "Reef Octopus Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d6 poison damage and Off-Guard (1 round)\n\n**Stage 3** 1d8 poison damage and Off-Guard (1 round)"

  - name: "Writhing Arms"
    desc: "`pf2:2`  The reef octopus makes up to four arm Strikes with different arms, each against a different target. These attacks count toward the octopus's multiple attack penalty, but the multiple attack penalty doesn't increase until after it makes all of its attacks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Reef Octopus
creatures:
  - 1: Reef Octopus
```



The common reef octopus is a risky but valuable catch for coastal fishers.
