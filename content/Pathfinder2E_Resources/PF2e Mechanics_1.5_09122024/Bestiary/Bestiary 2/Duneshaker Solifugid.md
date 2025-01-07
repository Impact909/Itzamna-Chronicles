---
title: "Duneshaker Solifugid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.K6KSUdllhmBKVT5s" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Duneshaker Solifugid"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Duneshaker Solifugid"
level: "Creature 18"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +35, Stealth: +33"
abilityMods: [9, 7, 7, -5, 4, -4]
speed: 50 feet,  burrow 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +31, __Ref__ +33, __Will__ +28"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (reach 10 feet)\n__Damage__  4d10 + 17 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, reach 20 feet)\n__Damage__  3d10 + 17 slashing"

  - name: "Earth Shaker"
    desc: " (move) Each turn, the first time the duneshaker solifugid is adjacent to a Large or smaller creature during a move action it's using, that creature must succeed at a DC 39 Reflex check save or fall [[Conditions/Prone|Prone]]."

  - name: "Pounce"
    desc: "`pf2:1`  The duneshaker solifugid Strides and makes a Strike at the end of that movement. If the duneshaker solifugid began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Venom Spray"
    desc: "`pf2:2` (poison) The duneshaker solifugid spews toxic barbs at all creatures in a 30-foot cone. Each creature within the area takes 10d6 poison damage (DC 39 Fortitude check save). A creature that fails its saving throw is [[Conditions/Blinded|Blinded]] for 1d6 rounds (or permanently on a critical failure).\n\nThe duneshaker solifugid can't use Venom Spray again for 1d4 rounds."
 
```

```encounter-table
name: Duneshaker Solifugid
creatures:
  - 1: Duneshaker Solifugid
```



The largest solifugids, duneshakers, are so immense that their movements make the terrain around them tremble. They can prey on creatures the size of mammoths or even larger.
