---
title: "Xulgath Leader (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nNurFmFBSPGlGmuq" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Xulgath Leader (BB)"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Xulgath Leader (BB)"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[xulgath]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11, Intimidation: +6, Stealth: +6"
abilityMods: [4, 1, 2, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +6, __Will__ +9"
hp: 44
health:
  - name: ""
  - name: HP
    desc: "44"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]], 4x [[Equipment/Javelin|Javelin]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "Stench"
    desc: "  A creature that comes within 30-foot emanation of the xulgath and can smell the xulgath must attempt a DC 19 Fortitude check save. On a failure, the creature takes a -1 status penalty to all checks and DCs until it uses an action to retch. A creature that succeeds at its save isn't affected by any xulgaths' stenches for 1 minute _(Use [[Conditions/Sickened|Sickened 1]])_."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+11 (sweep)\n__Damage__  1d10 + 6 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d6 + 6 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile)\n__Damage__  1d4 + 6 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+8 (thrown 30 ft.)\n__Damage__  1d6 + 4 piercing"

  - name: "Swipe"
    desc: "`pf2:2`  The xulgath boss makes two Strikes with their greataxe against two adjacent foes, both of whom are within their reach, with a +1 circumstance bonus. The second attack uses the same multiple attack penalty as the first, but attacks the xulgath boss makes after this take a -10 multiple attack penalty (or a -8 multiple attack penalty for its claw)."
 
```

```encounter-table
name: Xulgath Leader (BB)
creatures:
  - 1: Xulgath Leader (BB)
```



Xulgath leaders exhibit greater strength and more affinity for violence than other members of a xulgath community.
