---
title: "Giant Frog"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vXG4LWhT8NMVpFRU" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Giant Frog"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Frog"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +6, Stealth: +7"
abilityMods: [3, 2, 3, -4, 2, -1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +8, __Ref__ +7, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+8 ()\n__Damage__  1d6 + 3 piercing plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+8 (reach 15 feet)\n__Damage__ "

  - name: "Sticky Feet"
    desc: "  Giant frogs are not off-guard when [[Actions/Balance|Balancing]] on a narrow surface, and they gain a +4 bonus to Reflex saves to avoid falling."

  - name: "Tongue Grab"
    desc: "  A creature hit by the giant frog's tongue becomes [[Conditions/Grabbed|Grabbed]] by the giant frog. The creature isn't [[Conditions/Immobilized|Immobilized]], but it can't move beyond the reach of the frog's tongue. A creature can sever the tongue with a Strike against AC 13 that deals at least 2 slashing damage.\n\nThis deals no damage to the frog but prevents it from using its tongue Strike until it regrows its tongue, which takes a week."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Frog
creatures:
  - 1: Giant Frog
```



Giant frogs can grow up to 6 feet long and weigh over 200 pounds, with rows of razor-sharp teeth lining their gaping mouths.
