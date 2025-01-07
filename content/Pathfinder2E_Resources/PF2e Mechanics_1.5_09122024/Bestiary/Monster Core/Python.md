---
title: "Python"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.X2Eifhnpt3ANAoTk" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Python"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Python"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +6, Stealth: +6, Survival: +4"
abilityMods: [3, 3, 3, -4, 1, -2]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +10, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Tighten Coils"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the python attempts to [[Actions/Escape|Escape]].\n* * *\n\n**Effect** The DC of the Escape check is increased by 2."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+8 ()\n__Damage__  1d8 + 3 piercing plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8 bludgeoning, DC 17 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Wrap in Coils"
    desc: "`pf2:1`  **Requirements** A Medium or smaller creature is [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in the python's jaws.\n* * *\n\n**Effect** The python moves the creature into its coils, freeing its jaws to make attacks, then uses Constrict against the creature. The python's coils can hold one creature."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Python
creatures:
  - 1: Python
```



This nonvenomous family of snakes is rarely a threat to anything but small mammals and birds, hunting by coiling around prey and crushing victims with their powerful muscles. Nonetheless, larger pythons can be dangerous due to their strength. Herpetologists sometimes keep pythons as pets.

* * *

Snakes come in an array of forms, from jungle-dwelling constrictors that wrap around their prey to venomous vipers with deadly bites. Regardless, all snakes consume their prey whole by unhinging their jaws and using powerful muscles to move the food down their throats and into their stomachs.
