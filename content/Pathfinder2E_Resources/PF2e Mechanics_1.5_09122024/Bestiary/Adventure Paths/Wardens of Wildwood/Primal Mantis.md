---
title: "Primal Mantis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aZzF399ctRrMTVae" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Primal Mantis"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Primal Mantis"
level: "Creature 11"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +25, Stealth: +22"
abilityMods: [8, 3, 5, -5, 3, -2]
speed: 50 feet,  climb 50 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +20, __Will__ +18"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+25 (reach 10 feet)\n__Damage__  2d12 + 14 piercing"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+24 (agile, reach 20 feet)\n__Damage__  2d10 + 14 piercing plus grab"

  - name: "Primal Innate Spells"
    desc: "DC 27, attack +19; __6th __  _[[Spells/Chain Lightning|Chain Lightning]]_; __5th __  _[[Spells/Howling Blizzard|Howling Blizzard]]_; __4th __  _[[Spells/Fly|Fly]]_"

  - name: "Fling"
    desc: "`pf2:1`  The deadly mantis flings a [[Conditions/Grabbed|Grabbed]] creature into the air, up to 30 feet overhead and up to 30 feet away from the mantis (the creature takes damage from the fall as normal). If the flung creature lands on another creature, the creature it lands on takes the same amount of bludgeoning damage with a DC 31 Reflex check save."

  - name: "Leaping Grab"
    desc: "`pf2:2`  The mantis Leaps up to 40 feet vertically and 20 feet horizontally. At any point during the jump, it can make a leg Strike. If it hits, it automatically [[Bestiary Ability Glossary/Grab|Grabs]] the target, bringing the creature along until the end of the jump."

  - name: "Primal Toll"
    desc: "  The primal mantis takes 2d6 mental damage whenever it casts a primal innate spell."

  - name: "Rending Mandibles"
    desc: "`pf2:1`  The mantis makes a mandibles Strike against a creature it has [[Conditions/Grabbed|Grabbed]]. If that Strike hits and the creature is wearing armor with Hardness 12 or lower, the armor is broken. This Strike doesn't further damage armor that's already broken."

  - name: "Sudden Strike"
    desc: "  On the first round of combat, creatures that haven't acted are [[Conditions/Off-Guard|Off-Guard]] to the deadly mantis."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Primal Mantis
creatures:
  - 1: Primal Mantis
```


Variant deadly mantis

These gigantic mantids make their homes within prehistoric forests.

* * *

These predators possess lightning-quick forelegs and a bone-breaking bite.
