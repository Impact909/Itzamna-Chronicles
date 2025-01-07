---
title: "Desert Manticore"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sIQMZfi86vfC0jFS" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Desert Manticore"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Desert Manticore"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Kelish, Osiriani"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +25, Deception: +22, Intimidation: +26, Stealth: +22"
abilityMods: [7, 2, 5, -2, 2, 4]
speed: 30 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +22, __Will__ +22"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  poison"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Indomitable Beast"
    desc: "`pf2:r`  **Frequency** once per day\n\n**Trigger** The desert manticore is reduced to 0 HP\n* * *\n\n**Effect** The desert manticore avoids being knocked out and remains at 1 HP, then can make a stinger Strike against a creature in its reach."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 ()\n__Damage__  4d8 + 10 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+25 (agile)\n__Damage__  4d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+25 (reach 10 feet)\n__Damage__  3d6 + 10 piercing plus manticore-venom"

  - name: "Manticore Venom"
    desc: " (poison) **Saving Throw** DC 32 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 3d8 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 4d8 poison damage and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 5d8 poison damage and [[Conditions/Drained|Drained 3]] (1 round)"

  - name: "Scorpion Sting"
    desc: "`pf2:2`  The desert manticore Strikes an [[Conditions/Off-Guard|Off-Guard]] creature with its stinger. The attack injects venom deeply, dealing an additional 4d8 poison damage and giving the target a –2 circumstance penalty to their initial save against the poison."

  - name: "Venomous Flight"
    desc: "`pf2:2`  The desert manticore Flies twice, dripping venom from its stinger. It chooses a creature it flew directly above during the flight, which is exposed to manticore venom. The desert manticore cannot fly further than 60 feet above the target or the venom becomes too dispersed in fall to take effect."
 
```

```encounter-table
name: Desert Manticore
creatures:
  - 1: Desert Manticore
```




