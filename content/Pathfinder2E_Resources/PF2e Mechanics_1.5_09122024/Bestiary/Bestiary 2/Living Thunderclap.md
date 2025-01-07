---
title: "Living Thunderclap"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pRE2JFAN5iPKrDmp" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Living Thunderclap"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Living Thunderclap"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Stealth: +12"
abilityMods: [3, 4, 2, -3, 1, 0]
speed:  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +10, __Ref__ +12, __Will__ +9"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  bleed,  paralyzed,  poison,  sleep,  sonic"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Gust"
    desc: "+14 (agile, finesse)\n__Damage__  2d6 + 6 bludgeoning plus push"

  - name: "**Ranged** `pf2:1` Lightning Bolt"
    desc: "+14 (electricity, range increment 50 feet)\n__Damage__  2d12 electricity"

  - name: "Swiftness"
    desc: "  The living thunderclap doesn't trigger reactions when it moves."

  - name: "Thunderbolt"
    desc: "`pf2:2` (electricity,primal,sonic) The living thunderclap emits a bolt of lightning that crashes with deafening thunder. The living thunderclap makes a lightning bolt Strike that deals 1d12 electricity damage. If it hits, the target and any creatures within a 15-foot emanation around the target take 2d6 sonic damage and must attempt a DC 18 Fortitude check save.\n\nAny creature that fails its save is also [[Conditions/Deafened|Deafened]] for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Living Thunderclap
creatures:
  - 1: Living Thunderclap
```



A living thunderclap is a humanoid-shaped storm cloud that cracks and booms with thunder.
