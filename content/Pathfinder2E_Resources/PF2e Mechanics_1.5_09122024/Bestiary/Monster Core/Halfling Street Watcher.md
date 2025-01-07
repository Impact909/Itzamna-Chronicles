---
title: "Halfling Street Watcher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.oAnwUNBMERuIfQjR" 
tags:
  - pf2e/creature/type/halfling
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Halfling Street Watcher"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Halfling Street Watcher"
level: "Creature -1"

alignment: ""
size: "Small"
trait_01: [[halfling]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; "
languages: "Common, Halfling"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +4, Diplomacy: +3, Stealth: +5, Thievery: +5"
abilityMods: [-1, 3, 1, 0, 3, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +3, __Ref__ +8, __Will__ +5"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Frying Pan|Frying Pan]], [[Equipment/Halfling Sling Staff|Halfling Sling Staff]], [[Equipment/Leather Armor|Leather Armor]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Frying Pan"
    desc: "+9 (fatal d8)\n__Damage__  1d4 - 1 bludgeoning"

  - name: "**Ranged** `pf2:1` Halfling Sling Staff"
    desc: "+7 (propulsive, range increment 80 feet, reload 1)\n__Damage__  1d10 - 1 bludgeoning"

  - name: "Keen Eyes"
    desc: "  The halfling gains a +2 circumstance bonus when using the [[Actions/Seek|Seek]] action to find [[Conditions/Hidden|Hidden]] or undetected creatures within 30 feet of it.\n\nWhenever the halfling targets a creature that is [[Conditions/Concealed|Concealed]] or hidden from them, reduce the DC of the flat check to 3 for a concealed target or 9 for a hidden one."
 
```

```encounter-table
name: Halfling Street Watcher
creatures:
  - 1: Halfling Street Watcher
```



Halflings' keen sight makes them excellent street watchers. Though the job rarely calls for fighting, most street watchers cover themselves head to ankle in whatever armor and weapons they manage to get their hands on.

* * *

Despite their small stature, a halfling can prove to be a mighty foe if you find yourself on the wrong side of their frying pan.
