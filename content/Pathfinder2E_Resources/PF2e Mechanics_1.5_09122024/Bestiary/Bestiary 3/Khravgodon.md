---
title: "Khravgodon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ft9kFU8rByZ0u0RF" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Khravgodon"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Khravgodon"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +21, Stealth: +18, Survival: +18"
abilityMods: [6, 3, 5, -4, 3, 0]
speed: 30 feet,  burrow 15 feet,  climb 15 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +18, __Will__ +16; +2 circumstance to all saves vs. disease"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160; __Resistances__ acid 10, poison 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Feign Death"
    desc: "`pf2:r`  **Trigger** The khravgodon is reduced below 70 HP\n* * *\n\n**Effect** The khravgodon collapses. It is [[Conditions/Off-Guard|Off-Guard]] and can use actions that require only its mind, but any other action ends the ruse.\n\nA successful DC 18 Perception check check to [[Actions/Seek|Seek]] or DC 18 Medicine check check to [[Actions/Recall Knowledge|Recall Knowledge]] is required to determine that the animal is not, in fact, dead."

  - name: "Revived Retaliation"
    desc: "`pf2:r`  **Trigger** The khravgodon is attacked or disturbed by a creature within reach while Feigning Death\n* * *\n\n**Effect** The khravgodon Strikes the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (deadly d12)\n__Damage__  2d12 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile)\n__Damage__  2d10 + 9 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+21 (reach 20 feet)\n__Damage__  2d6 + 9 bludgeoning plus grab"

  - name: "Crush Chitin"
    desc: "`pf2:1`  **Requirements** The khravgodon has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The khravgodon bites the creature, dealing 2d12+9 piercing damage (DC 28 Fortitude check save) that ignores the first 5 of the target's Hardness or resistance to physical damage. On a failed save, the target also takes a -2 circumstance penalty to AC for 1 round.\n\n[[Bestiary Effects/Effect_ Crush Chitin|Effect: Crush Chitin]]"

  - name: "Grasping Tail"
    desc: "  A khravgodon can drag a Large or smaller creature it has [[Conditions/Grabbed|Grabbed]] with its tail along with it when it Strides."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Khravgodon
creatures:
  - 1: Khravgodon
```



Few creatures can shrug off an ankhrav's acid and crunch its chitin like a khravgodon.

* * *

Few creatures have survived as long and in as many environments as the opossum.
