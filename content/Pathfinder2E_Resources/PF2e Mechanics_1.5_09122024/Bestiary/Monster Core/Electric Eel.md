---
title: "Electric Eel"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.B6guF4lVc46qJ84c" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Electric Eel"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Electric Eel"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +7"
abilityMods: [1, 2, 2, -5, 1, -1]
speed: 5 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +7, __Ref__ +7, __Will__ +4"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18; __Resistances__ electricity 7"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+6 ()\n__Damage__  1d6 + 3 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+6 (agile)\n__Damage__  1d4 + 1 bludgeoning plus stunning-shock 1d4 electricity plus stunning-shock"

  - name: "Stunning Shock"
    desc: " (incapacitation) A creature critically hit by the electric eel's tail must attempt a DC 17 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 2]].\n\n**Critical Failure** The creature is [[Conditions/Stunned|Stunned 3]]."
 
```

```encounter-table
name: Electric Eel
creatures:
  - 1: Electric Eel
```



Usually found in freshwater rivers and lakes, an electric eel is not particularly aggressive, but its ability to stun predators and prey alike can be dangerous to larger creatures searching for their next meal. Electric eels are more closely related to catfish than to other eels.

* * *

Although these long, narrow fish share similarities in appearance, eels are a diverse group of creatures.
