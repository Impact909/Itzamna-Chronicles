---
title: "Dire Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3X2T0ldZpHptn2pf" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Dire Wolf"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dire Wolf"
level: "Creature 3"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +10, Stealth: +8, Survival: +10"
abilityMods: [5, 3, 4, -4, 3, -2]
speed: 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +8, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 20 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (reach 10 feet)\n__Damage__  1d10 + 5 piercing plus grab,knockdown"

  - name: "Pack Attack"
    desc: "  The dire wolf's Strikes deal 1d6 extra damage to creatures within reach of at least two of the wolf's allies."

  - name: "Worry"
    desc: "`pf2:1` (attack) **Requirements** The dire wolf has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its jaws\n* * *\n\n**Effect** The dire wolf fiercely shakes the creature with its teeth, dealing 1d10+2 piercing damage with a DC 20 Fortitude check save."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Dire Wolf
creatures:
  - 1: Dire Wolf
```



Much larger and more foul-tempered than their common cousins, dire wolves haunt primeval lands that accommodate their massive size and proportionately large hunting grounds and appetites. Orcs are fond of using dire wolves as mounts, finding their vicious tempers perfect for hunting and warfare. Dire wolves are far more likely to prey on humanoids than ordinary wolves, considering them nothing but another kind of smaller, nutritious animal.

* * *

Wolves roam forests, hills, and other wild lands, where they hunt in packs to beleaguer and surround their prey before going in for the kill. Like most predatory animals, wolves prefer to attack the weakest or most vulnerable prey they can find.
