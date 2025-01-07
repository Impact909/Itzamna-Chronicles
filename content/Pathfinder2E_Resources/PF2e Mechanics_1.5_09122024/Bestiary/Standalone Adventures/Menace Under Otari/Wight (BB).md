---
title: "Wight (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HRr89GIWRadHzoK4" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Wight (BB)"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Wight (BB)"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
trait_03: [[wight]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Intimidation: +9, Stealth: +8"
abilityMods: [4, 1, 4, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +6, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  poison,  unconscious,  bleed,  void"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]]"
abilities_mid:
  - name: ""
  - name: "Final Spite"
    desc: "`pf2:r`  When the wight is reduced to 0 Hit Points, it can use its reaction to make a Strike before being destroyed. It doesn't gain any Hit Points from corrupting spite on this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile)\n__Damage__  1d6 + 6 slashing plus corrupting-spite"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+12 (agile, versatile s)\n__Damage__  1d4 + 6 piercing plus corrupting-spite"

  - name: "Corrupting Spite"
    desc: " (divine,void) When the wight deals damage to a living creature with its claw or dagger Strike, the wight regains 2 void healing Hit Points and the target must succeed at a DC 17 Fortitude check save or take 2 damage that can't be healed. The wight can use corrupting spite multiple times, but a single creature can't take more than 8 unhealable damage.\n\nEach full night of rest heals 2 of the unhealable damage, and a full day of bed rest increases the recovery to 4 of the unhealable damage."
 
```

```encounter-table
name: Wight (BB)
creatures:
  - 1: Wight (BB)
```



Wights are undead humanoids that lurk in burial grounds, catacombs, or other places of the dead.
