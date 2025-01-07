---
title: "Holdfast"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Ir9TgxQnVwrlUCsa" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Holdfast"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Holdfast"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision, Scent (Imprecise) 30 Feet, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +11, Stealth: +12"
abilityMods: [5, 4, 3, -4, 2, 0]
speed: 30 feet,  burrow 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +12, __Will__ +8"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hold Tight"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the holdfast's jaws takes damage from another creature's Strike\n* * *\n\n**Effect** The holdfast Constricts the creature in its jaws."

  - name: "Lithe"
    desc: "  A holdfast treats any tight space it can barely fit its head in or wider as difficult terrain and doesn't need to [[Actions/Squeeze|Squeeze]] to move through it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d6 + 5 piercing plus grab"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+13 (agile)\n__Damage__  2d4 + 5 slashing"

  - name: "Burst from Below"
    desc: "`pf2:1`  The holdfast Burrows and then Strikes. If the holdfast began this movement [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+2 piercing plus crush throat, DC 21 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Crush Throat"
    desc: "  When a creature fails a save against the holdfast's Constrict, the creature's throat is held tight, stopping them from speaking as long as they're [[Conditions/Grabbed|Grabbed]]. This prevents the creature from casting spells with vocal incantations, as well as from using many sonic or auditory abilities."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Holdfast
creatures:
  - 1: Holdfast
```




