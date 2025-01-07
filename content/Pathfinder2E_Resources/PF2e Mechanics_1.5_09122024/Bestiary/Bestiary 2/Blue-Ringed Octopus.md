---
title: "Blue-Ringed Octopus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Vlyml3WJOdRviRah" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Blue-Ringed Octopus"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Blue-Ringed Octopus"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +7"
abilityMods: [0, 3, 1, -4, 3, 0]
speed:  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +3, __Ref__ +9, __Will__ +6"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Resistances__ cold 2"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+7 (finesse)\n__Damage__  1d6 piercing plus blue-ringed-octopus-venom"

  - name: "**Melee** `pf2:1` Arms"
    desc: "+6 ()\n__Damage__ "

  - name: "Blue-Ringed Octopus Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage (1 round)\n\n**Stage 3** 1d6 poison damage and [[Conditions/Paralyzed|Paralyzed]] (1 round)"

  - name: "Camouflage"
    desc: "  The blue-ringed octopus can change the color of its skin to [[Actions/Hide|Hide]] even if it doesn't have cover."

  - name: "Jet"
    desc: "`pf2:2`  The blue-ringed octopus moves up to 60 feet in a straight line through the water without triggering reactions."

  - name: "Toxic Bite"
    desc: "`pf2:1` (virulent) **Requirements** The blue-ringed octopus has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The blue-ringed octopus makes a beak Strike against the grabbed creature. If it hits, it injects additional poison, causing its venom to gain the virulent trait."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Blue-Ringed Octopus
creatures:
  - 1: Blue-Ringed Octopus
```



While relatively small, the blue-ringed octopus is particularly venomous for its size.
