---
title: "Greater Chimera"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.u4v3Du5cYg2C56sE" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Greater Chimera"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Greater Chimera"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +27, Stealth: +27"
abilityMods: [8, 4, 5, -2, 3, 1]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +23, __Will__ +20"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Three-Headed"
    desc: "  Any ability that would sever a greater chimera's head (such as a critical hit with a [[Equipment/Vorpal|Vorpal]] weapon) severs one head at random. Losing a head doesn't kill a chimera (as long as it has at least one head left), but it does prevent it from making Strikes with the lost head or using any abilities granted by the head."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile)\n__Damage__  3d8 + 8 slashing"

  - name: "Multiple Reactions"
    desc: "  A greater chimera gains 2 extra reactions each round that it can use only to make Reactive Strikes. It must use a different head for each reaction, and it can't use more than one on the same triggering action. If it loses one of its heads, it also loses one of these extra reactions."

  - name: "Three-Headed Strike"
    desc: "`pf2:2`  The greater chimera makes a Strike with each of its heads, each at a –2 penalty and targeting a different creature. These Strikes count as only one attack for the greater chimera's multiple attack penalty, and the penalty doesn't increase until after it has made all three attacks."
 
```

```encounter-table
name: Greater Chimera
creatures:
  - 1: Greater Chimera
```




