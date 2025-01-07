---
title: Shrouded Assailant
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder Dark Archive
aliases: "Actor.xwXUDqm2L5z0uv8R" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Dark Archive"
name: "Shrouded Assailant"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 33
sourcebook: "_Pathfinder Dark Archive_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +26, __Ref__ +32, __Will__ +35"
hp: 230
health:
  - name: ""
  - name: "HP"
    desc: "230, spirit; __Immunities__  object immunities; __Resistances__ all damage 20 (except ghost touch; double resistance vs. non-magical)"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: " +33"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A spirit steps out of a covered mirror, pulling off and becoming shrouded in the cloth, which reveals the mirror. The shrouded figure attacks the living until the cloth is yanked off, which banishes the formless spirit."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 43 Thievery check (master) to steal the cloth before the spirit manifests, or DC 47 Athletics check to pull the cloth off the spirit after it manifests"
attacks:
  - name: ""

  - name: "Don Shroud"
    desc: "`pf2:r` (occult) **Trigger** A creature enters the area\n* * *\n\n**Effect** The spirit steps out of the mirror, wearing the cloth as a shroud and revealing the mirror. The triggering creature is [[Conditions/Frightened|Frightened 3]] unless they succeed at a DC 38 Will check save. The haunt then rolls initiative."
  - name: "Melee"
    desc: "Shrouded Touch +33 () "

  - name: "Routine"
    desc: "(3 actions) The spirit uses 3 actions to Step, fly 60 feet, or Strike, in any order. On a successful Strike the spirit's target is [[Conditions/Frightened|Frightened 1]], and on a critical success, the target is [[Conditions/Frightened|Frightened 2]]."
  - name: "Reset"
    desc: "The haunt can be reset if the mirror is covered in a cloth or shroud."
```

```encounter-table
name: Shrouded Assailant
creatures:
  - 1: Shrouded Assailant
```

