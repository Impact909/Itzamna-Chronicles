---
title: "Reefclaw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.yo4S98AnB2bhcNn9" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Reefclaw"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Reefclaw"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[aquatic]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4"
abilityMods: [1, 4, 2, -3, 1, 1]
speed: 5 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
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
    desc: "+9 (finesse)\n__Damage__  1d6 + 1 slashing plus grab,reefclaw-venom"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6 bludgeoning, DC 17 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Reefclaw Venom"
    desc: " (poison) **Saving Throw** DC 17 Fortitude check\n* * *\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 1d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Reefclaw
creatures:
  - 1: Reefclaw
```



Reefclaws are aquatic monsters that resemble huge shrimp or lobsters. As one might expect from its name, a reefclaw's oversized claws are powerful weapons with a viselike grip and the ability to inject potent venom into unfortunate prey.

Though reefclaws can't speak, they are intelligent enough to understand the local language of humanoids near their hunting grounds. The creatures sometimes listen to conversations, either to gain intelligence on the best place to ambush aquatic or land-dwelling prey, or merely for entertainment value—reefclaws are particularly fond of listening to people with high-pitched voices. Reefclaws are usually solitary hunters, but small swarms of female reefclaws have been known to gather around a single male for mating purposes or together for the communal raising of their broods. In the latter case, the females will perform widespread hunts in order to bring back a large enough bounty to feed their young. Such hunting parties are extremely dangerous—they've been known to tip over small fishing boats and attack those who fall overboard.

Once a reefclaw has decided upon a course of action, it follows through even if doing so spells its own end. More than one reefclaw survivor has said that the creature released its bone-crushing grasp only after the brains were leaking from its broken skull, and even then, the reefclaw was able to perform a terrible last slash as part of its dying breath. During mating season, female reefclaws are often a little more pragmatic and release their prey before endangering themselves and their offspring.

Despite their intelligence and the accompanying moral quandaries, reefclaws frequently find their way onto the dinner plates of land-dwelling hunters such as humans and hobgoblins. According to those who have a taste for reefclaw flesh, the meat is either delectably sweet (for reefclaws raised in colder waters) or slightly tangy (in the case of warm-water reefclaws). Most people who know of reefclaws' intellect find the act of eating them distasteful, but this does not dissuade unscrupulous nobles in coastal regions, for whom reefclaw meat is a delicacy well worth the expense. Likewise, fishers whose focus is on the bottom line of their ledgers are more than willing to hunt the dangerous creatures—or, even better, hire out the task to naive adventurers.
