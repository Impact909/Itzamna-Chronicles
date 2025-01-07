---
title: "Giant Opossum"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.03x6WtV943TdzLb2" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Giant Opossum"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Giant Opossum"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +8, Survival: +6"
abilityMods: [4, 2, 3, -4, 2, 0]
speed: 30 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +11, __Ref__ +8, __Will__ +5; +2 circumstance to all saves vs. disease"
hp: 35
health:
  - name: ""
  - name: HP
    desc: "35; __Resistances__ poison 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Feign Death"
    desc: "`pf2:r`  **Trigger** The opossum is reduced below 15 HP\n* * *\n\n**Effect** The opossum collapses. It is [[Conditions/Off-Guard|Off-Guard]] and can use actions that require only its mind, but any other action ends the ruse.\n\nA successful DC 18 Perception check check to [[Actions/Seek|Seek]] or DC 18 Medicine check check to [[Actions/Recall Knowledge|Recall Knowledge]] is required to determine that the animal is not, in fact, dead."

  - name: "Revived Retaliation"
    desc: "`pf2:r`  **Trigger** The opossum is attacked or disturbed by a creature within reach while Feigning Death\n* * *\n\n**Effect** The opossum Strikes the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (deadly d10)\n__Damage__  1d10 + 4 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+10 (reach 15 feet)\n__Damage__  1d4 + 4 bludgeoning plus grab"

  - name: "Grasping Tail"
    desc: "  A giant opossum can drag a Small or Tiny creature it has [[Conditions/Grabbed|Grabbed]] with its tail along with it when it Strides."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Opossum
creatures:
  - 1: Giant Opossum
```



Larger species of opossum can eat nearly anything human-sized or smaller.

* * *

Few creatures have survived as long and in as many environments as the opossum.
