---
title: "Giant Whiptail Centipede"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gEdc3VO6aUIb7m6X" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Giant Whiptail Centipede"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Whiptail Centipede"
level: "Creature 3"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +10, Stealth: +8"
abilityMods: [4, 2, 4, -5, 2, -4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +11, __Ref__ +9, __Will__ +7"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+11 (reach 10 feet)\n__Damage__  1d10 + 6 piercing plus whiptail-centipede-venom"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+11 (agile, reach 15 feet)\n__Damage__  1d6 + 6 bludgeoning plus knockdown"

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tail Only)]]"
    desc: "`pf2:r`  Tail Only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Undulate"
    desc: "`pf2:1`  The giant whiptail centipede Strides or Steps. During this movement, it can pass through spaces as narrow as 5 feet without Squeezing."

  - name: "Whiptail Centipede Venom"
    desc: " (poison) **Saving Throw** DC 19 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d10 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 2d10 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** 2d10 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Giant Whiptail Centipede
creatures:
  - 1: Giant Whiptail Centipede
```



Whiptail centipedes are sleek and swift tunnel predators.
