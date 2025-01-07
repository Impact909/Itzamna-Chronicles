---
title: "Lawn Crawfish"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MIS8fmxfuJuubvlo" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Lawn Crawfish"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Little Trouble in Big Absalom"
name: "Lawn Crawfish"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[aquatic]]
trait_03: [[chaotic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4"
abilityMods: [1, 4, 2, -3, 1, 1]
speed: 25 feet,  burrow 10 feet,  swim 30 feet
sourcebook: "_Pathfinder Adventure: Little Trouble in Big Absalom_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +7, __Ref__ +9, __Will__ +4"
hp: 17
health:
  - name: ""
  - name: HP
    desc: "17"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Death Frenzy"
    desc: "`pf2:r`  **Trigger** The reefclaw is reduced to 0 Hit Points.\n* * *\n\n**Effect** The reefclaw makes a claw Strike before dying."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (finesse)\n__Damage__  1d6 + 1 slashing plus crawfish-venom,grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6 bludgeoning, DC 17 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crawfish Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)."

  - name: "Grab"
    desc: "`pf2:1`  **Requirements** The monster's last action was a success with a Strike that lists Grab in its damage entry, or it has a creature grabbed using this action.\n* * *\n\n**Effect** The monster automatically Grabs the target until the end of the monster's next turn. The creature is grabbed by whichever body part the monster attacked with, and that body part can't be used to Strike creatures until the grab is ended. Using Grab extends the duration of the monster's Grab until the end of its next turn for all creatures grabbed by it. A grabbed creature can use the Escape action to get out of the grab, and the Grab ends for a grabbed creatures if the monster moves away from it."
 
```

```encounter-table
name: Lawn Crawfish
creatures:
  - 1: Lawn Crawfish
```



Reefclaws are aquatic monsters that resemble huge shrimp or lobsters. As one might expect from its name, a reefclaw's oversized claws are powerful weapons with their vicelike grip and the ability to inject potent venom into unfortunate prey.

While reefclaws can't speak, they are intelligent enough to understand the local language of humanoids near their hunting grounds. The creatures sometimes listen to conversations, either to gain intelligence on the best place to ambush aquatic or land-dwelling prey, or merely for entertainment value-reefclaws are particularly fond of listening to people with high-pitched voices. Reefclaws are usually solitary hunters, but small swarms of female reefclaws have been known to gather around a single male for mating purposes or together for the communal raising of their broods. In the latter case, the females will perform widespread hunts in order to bring back a large enough bounty to feed their young. Such hunting parties are extremely dangerous-they've been known to tip over small flshing boats and attack those who fall overboard.

Once a reefclaw has decided upon a course of action, it follows through even if doing so spells its own end. More than one reefclaw survivor has said that the creature released its bone-crushing grasp only after its brains were leaking from its broken skull, and even then the reefclaw was able to perform a terrible last slash as part of its dying breath. During mating season, female reefclaws are often a little more pragmatic and release their prey before endangering themselves and their offspring.

Despite their intelligence and the accompanying moral quandaries, reefclaws frequently find their way onto the dinner plates of land-dwelling hunters such as humans and hobgoblins. According to those who have a taste for reefclaw flesh, the meat is either delectably sweet or slightly tangy (in the case of warm-water reefclaws). Most civilized people who know of reefclaws' intellect find the act of eating them distasteful, but this does not dissuade unscrupulous nobles in coastal regions, for whom reefclaw meat is a delicacy well worth the expense. Likewise, fisherfolk whose focus is on the bottom line of their ledgers are more than willing to hunt the dangerous creatures-or, even better, hire out the task to naive adventurers.
