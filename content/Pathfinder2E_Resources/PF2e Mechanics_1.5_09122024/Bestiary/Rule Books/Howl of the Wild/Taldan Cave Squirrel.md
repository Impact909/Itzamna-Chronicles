---
title: "Taldan Cave Squirrel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QxjPkChDOQbArv5I" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Taldan Cave Squirrel"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Taldan Cave Squirrel"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 40 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Athletics: +12, Survival: +13"
abilityMods: [4, 4, 5, -4, 1, 2]
speed: 30 feet,  burrow 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +15, __Will__ +9"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95"
abilities_top:
  - name: ""

  - name: "Studded Cheeks"
    desc: "  The cave squirrel can store up to six gems in its cheeks. It typically begins combat with all six, and it loses a gem each time it uses gem spit."

abilities_mid:
  - name: ""
  - name: "Defensive Scream"
    desc: "`pf2:r` (auditory) **Trigger** The cave squirrel rolls initiative or has taken damage before initiative\n* * *\n\n**Effect** The cave squirrel lets out an ear-piercing shriek, alerting any other cave squirrels in the area to its plight. It uses Screaming Force."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (agile)\n__Damage__  2d6 + 4 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile)\n__Damage__  2d8 + 4 slashing"

  - name: "**Ranged** `pf2:1` Gem Spit"
    desc: "+15 (range 20 feet)\n__Damage__  2d8 + 6 bludgeoning plus concussive-gem"

  - name: "Concussive Gem"
    desc: "  On a critical hit on a gem spit Strike, the target must succeed at a DC 22 Fortitude check save or become [[Conditions/Stunned|Stunned 1]]."

  - name: "Forage for Gems"
    desc: "`pf2:2`  The cave squirrel dives underground in search of gems. The cave squirrel Burrows up to its Speed. It must end its movement back on the surface. During its burrow, it happens upon 1d4 cheap gems (such as salt or quartz), which it stuffs in its cheeks, up to its maximum of 6."

  - name: "Natural Speed"
    desc: "  A cave squirrel isn't affected by difficult terrain from earth or stone."

  - name: "Screaming Force"
    desc: "`pf2:1` (auditory,sonic) The cave squirrel lets out a terrible scream. Non–cave squirrel creatures within 30 feet must succeed at a DC 22 Fortitude check save or take 2d10 sonic damage. On a critical failure, a creature is [[Conditions/Deafened|Deafened]] for 1 minute. The cave squirrel can't use Screaming Force again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Taldan Cave Squirrel
creatures:
  - 1: Taldan Cave Squirrel
```




