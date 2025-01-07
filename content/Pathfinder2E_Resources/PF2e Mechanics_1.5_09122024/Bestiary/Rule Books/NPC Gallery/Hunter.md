---
title: "Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bakGC6p6XYJXDzox" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Hunter"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Hunter"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Medicine: +15, Nature: +17, Stealth: +17, Survival: +17, Forest Lore: +13"
abilityMods: [4, 4, 2, 1, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +17, __Will__ +15"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|+1 Composite Longbow]], [[Equipment/Dagger|Dagger]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Leather Armor|Leather Armor]], 60x [[Equipment/Arrows|Arrows]]"
  - name: "Forager"
    desc: "  While using Survival to [[Actions/Subsist|Subsist]], if the tracker rolls a failure or a critical failure, they get a success instead. If the tracker rolls a success, they can provide food for 16 additional creatures that eat about as much as a human, or 32 creatures on a critical success."

  - name: "Forest Walker"
    desc: "  The hunter ignores the effects of difficult terrain from a forest environment. They can [[Actions/Sneak|Sneak]] through underbrush without the need to attempt a Stealth check as long as the hunter moves no more than 5 feet at a time and is not within 10 feet of an enemy at any point during their movement."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+18 (agile, finesse, versatile s)\n__Damage__  1d4 + 9 piercing"

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+18 (agile, finesse, versatile s)\n__Damage__  1d6 + 9 piercing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+18 (deadly d10, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 8 piercing"

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) The hunter designates a single creature they can see and hear, or one they're Tracking, as their prey. The hunter gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] the prey and to Survival checks to [[Actions/Track|Track]] the prey.\n\nThe first time the hunter hits the designated prey in a round, they deal an additional 1d8 precision damage. The hunter also ignores the penalty for making ranged attacks within their second range increment.\n\nThese effects last until the hunter uses Hunt Prey again."
 
```

```encounter-table
name: Hunter
creatures:
  - 1: Hunter
```



As is reflected in the many depictions of an elk-headed Erastil, god of the hunt, the hunter is very much a creature of the forest, known by the forest and familiar with every aspect of it. After all, the final determination of who is the hunter and who is prey often depends on who is able to make an ally of the terrain.

* * *

From the managed and cultivated forests that support villages to the tree-covered crown lands where only nobles and their servants are permitted to hunt, forests provide. To communities, forests provide fuel, food, medicine, and raw materials, while royally protected forests provide food for the nobles' table and a source of entertainment in the form of organized hunts. Even the ancient woods untouched by mortal hand or blade provide bards with settings where legends happened and could happen again. Many find the forest depths unsettling, but others live their lives among the trees and alongside the creatures that make their homes there.
