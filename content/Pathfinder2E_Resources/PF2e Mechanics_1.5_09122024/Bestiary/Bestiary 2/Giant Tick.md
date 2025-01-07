---
title: "Giant Tick"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w6G8xA5xq166EJBW" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Giant Tick"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Tick"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +6"
abilityMods: [1, 3, 4, -5, 1, -5]
speed: 15 feet,  climb 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +9, __Ref__ +6, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hypostome"
    desc: "+8 (finesse)\n__Damage__  1d6 + 1 piercing plus attach,tick-fever"

  - name: "Attach"
    desc: "  When the giant tick Strikes a creature larger than itself, its barbed hypostome attaches it to that creature. This is similar to Grabbing the creature, but the giant tick moves with that creature rather than holding it in place. The giant tick is [[Conditions/Off-Guard|Off-Guard]] while attached. If the giant tick is killed or pushed away while attached to a creature on which it has used Blood Drain, that creature takes 1 bleed damage. Escaping the attachment or removing the giant tick in other ways doesn't cause bleed damage."

  - name: "Blood Drain"
    desc: "`pf2:1`  **Requirements** The giant tick is attached to a creature\n* * *\n\n**Effect** The giant tick uses its hypostome to drain blood from the creature it's attached to. This deals 1d4 damage, and the giant tick gains temporary Hit Points equal to the damage dealt. A creature that has its blood drained by a giant tick is [[Conditions/Drained|Drained 1]] until it receives healing (of any kind or amount)."

  - name: "Tick Fever"
    desc: " (disease) **Saving Throw** DC 17 Fortitude check\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"
 
```

```encounter-table
name: Giant Tick
creatures:
  - 1: Giant Tick
```



This grotesque tick is the size of a dog and scurries with surprising speed.
