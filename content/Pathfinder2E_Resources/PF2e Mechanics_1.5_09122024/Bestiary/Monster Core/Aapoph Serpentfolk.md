---
title: "Aapoph Serpentfolk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JVm9AfrAT9npvgNm" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/mutant
  - pf2e/creature/type/serpentfolk
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Aapoph Serpentfolk"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Aapoph Serpentfolk"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[mutant]]
trait_03: [[serpentfolk]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Sakvroth; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +11, Intimidation: +6"
abilityMods: [4, 2, 3, -1, 1, -1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +7, __Will__ +6; +2 status to will saves vs. mental"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|Scimitar]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+11 (forceful, sweep)\n__Damage__  1d6 + 6 slashing"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+11 ()\n__Damage__  1d8 + 6 piercing plus serpentfolk-venom"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+11 (agile)\n__Damage__  1d6 + 6 bludgeoning plus knockdown"

  - name: "Serpentfolk Venom"
    desc: " (poison) **Saving Throw** DC 20 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d4 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 2d4 poison damage and enfeebled 1 (1 round)"

  - name: "Slithering Attack"
    desc: "`pf2:1`  The aapoph serpentfolk makes one scimitar or fangs Strike and one tail Strike, each targeting a different creature. These attacks both count toward the aapoph's multiple attack penalty, but the penalty doesn't increase until after the aapoph makes both attacks."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Aapoph Serpentfolk
creatures:
  - 1: Aapoph Serpentfolk
```



Aapophs possess greater strength and stronger venom than their zyss kin, but they lack zyss's innate magic. Unlike their selfish superiors, aapophs are communal and group together to hunt, wrestle, and sleep curled together in pits.

Aapophs often have physical mutations—horns, vestigial tails, or spines protruding from their scales—yet these have little impact on their overall combat prowess—and combat prowess is the measure by which zyss judge them.

* * *

Before their ancient clash with humanity devastated their civilization, serpentfolk were masters of a sprawling underground empire. Their power was shattered and their god Ydersius decapitated (although not quite slain). The cunning, intelligence, and magical abilities of serpentfolk have diminished from their ancient heights, and most are born without these boons. This is partially the result of cruel genetic meddling among serpentfolk—though the ruling class, zyss, are born with an innate spellcasting ability, their blood runs thin, making them susceptible to wounds. Seen as the failures of the serpentfolk's experiments are the aapophs, who are strong but prone to mutation and lack innate spellcasting.

Today, the central realm of the Darklands retains the old name of the serpentfolk empire that once dominated this region—Sekamina. This name is also the source of the serpentfolk's Aklo title, sekmin, which they are often called in ancient texts. Serpentfolk dominion had declined before ghouls, gugs, umbral gnomes, and other forces. Yet their recent ventures have brought them back to a stronger place in the Darklands. Many serpentfolk sleeping in torpor in secluded vaults have awakened.

Zyss serpentfolk tend toward megalomania, with dreams of returning to their place of dominance. Many of their plans hinge on resurrecting Ydersius, their decapitated god. His headless body still thrashes about, mindless, in the Darklands, waiting to be reunited with his lost skull. Serpentfolk numbers are so small that reclaiming their dominance seems a distant dream, especially since their reproduction is slow. Though a parent can birth a dozen young at once, the gestation period lasts up to a decade, and the likelihood that even one will be zyss is low. There's no telling whether a child will be zyss or aapoph, regardless of parentage. A coveted zyss child is just as likely to arise from aapoph parents as from two zyss, and every serpentfolk colony has someone in charge of sorting the young, identifying the earliest signs of magic in them.
