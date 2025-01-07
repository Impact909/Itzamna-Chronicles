---
title: "Kuchisake-Onna"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.N0U7gFqFUAzFZzRy" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Kuchisake-Onna"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Kuchisake-Onna"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
trait_03: [[lawful]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +22, Intimidation: +27, Stealth: +26"
abilityMods: [4, 8, 4, 5, 6, 5]
speed: 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +22, __Ref__ +28, __Will__ +24"
hp: 252
health:
  - name: ""
  - name: HP
    desc: "252; __Weaknesses__ mental 10; __Resistances__ slashing 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x Silver Scissors"
abilities_mid:
  - name: ""
  - name: "Compulsive Counting"
    desc: "  When numerous small items are scattered before the kuchisake-onna, they compulsively begins to count them. The kuchisake-onna becomes [[Conditions/Off-Guard|Off-Guard]] to all creatures for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Silver Scissors"
    desc: "+30 (agile, backstabber, fatal d12, finesse)\n__Damage__  3d6 + 12 slashing"

  - name: "Am I Pretty?"
    desc: "`pf2:1`  The kuchisake-onna asks a single adjacent target, \"Am I pretty?\" The target must attempt a DC 35 Will check save. If it fails, it is [[Conditions/Immobilized|Immobilized]] for 1 round, and if it critically fails, it is [[Conditions/Paralyzed|Paralyzed]] for 1 round, though still able to respond to the question; this is a mental effect.\n\nIf the target responds \"No\", the kuchisake-onna makes two silver scissors Strikes against the target. If the target responds \"Yes\", the kuchisake-onna makes no Strikes this turn and must use Even Now? as their next action (waiting until the first action of their next turn, if necessary). If the target otherwise responds in a confusing or noncommittal manner, the kuchisake-onna becomes [[Conditions/Off-Guard|Off-Guard]] to all creatures for 1 round but can otherwise act normally."

  - name: "Even Now?"
    desc: "`pf2:1`  **Requirements** An adjacent creature previously targeted by Am I Pretty? answered \"Yes\"\n* * *\n\n**Effect** The kuchisake-onna takes off their mask, revealing their slit face and asking, \"Even now?\" The target must attempt a DC 35 Will check save.\n\nIf it fails, it is [[Conditions/Immobilized|Immobilized]] for 1 round, and if it critically fails, it is [[Conditions/Paralyzed|Paralyzed]] for 1 round, though still able to respond to the question; this is a mental effect.\n\nWhether the target responds \"Yes\" or \"No\", the kuchisake-onna makes two silver scissors Strikes against the target."

  - name: "Lingering Enmity"
    desc: "  The kuchisake-onna's silver scissors Strikes are manifestations of the toxic malice that created them and vanish when the kuchisake-onna is destroyed.\n\nWhen the kuchisake-onna has less than half their maximum Hit Points remaining, this concentrated enmity begins to leak out and make their attacks more vicious. Their silver scissors Strikes deal 6d6 persistent bleed damage.\n* * *\n\n_Note: Due to a later published errata this persistent damage is doubled on a critical hit. Due to the high damage potential for this creature's level that interaction may not be intended._"

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Silver Scissors\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Kuchisake-Onna
creatures:
  - 1: Kuchisake-Onna
```



A kuchisake-onna, or slit-mouthed woman, is a tall, masked figure who moves with an eerie grace. These horrors are infamous for trapping hapless mortals and asking them, "Am I pretty?" A "no" response leads to a gruesome death wrought by the silver scissors the kuchisake-onna carries. A "yes" prompts them to remove their mask, revealing the scars and cuts running from ear to ear, giving the impression of a terrible, ever-present grin. They then open their mouth to reveal sharp, needle-like teeth and ask another question: "Even now?" A "no" leads to the same gory death, while a "yes" prompts them to use their silver scissors and make the same cuts on the target's face while repeating: "Then I will make you like me."

There are a handful of methods to weasel out of this otherwise no-win scenario. Answering noncommittally, saying the kuchisake-onna looks "okay," or throwing several small, countable objects like rice or candy often provides enough time to run while the monster is distracted. Few are foolish enough to attack the kuchisake-onna, and those that live to tell the tale speak of a flashing flurry of scissor blades that match even a swordmaster's prowess.
