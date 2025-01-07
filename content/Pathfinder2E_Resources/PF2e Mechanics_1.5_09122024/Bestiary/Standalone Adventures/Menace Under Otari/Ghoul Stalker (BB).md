---
title: "Ghoul Stalker (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gEAnrez6I4VoCB8z" 
tags:
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Ghoul Stalker (BB)"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Ghoul Stalker (BB)"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[ghoul]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +8, Stealth: +7, Survival: +5"
abilityMods: [1, 4, 1, 1, 2, 2]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +4, __Ref__ +9, __Will__ +5"
hp: 16
health:
  - name: ""
  - name: HP
    desc: "16; __Immunities__  poison,  unconscious,  bleed,  void"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Stench"
    desc: "  A creature that comes within 10 feet of the ghoul and can smell the ghoul must attempt a DC 14 Fortitude check save. On a failure, the creature takes a -1 status penalty to all checks and DCs until it uses an action to retch ([[Conditions/Sickened|Sickened 1]]). A creature that succeeds at its save isn't affected by any ghoul's stench for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 (finesse)\n__Damage__  1d8 + 1 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+9 (agile, finesse)\n__Damage__  1d6 + 1 slashing"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) The ghoul devours a chunk of a creature that died within the last hour and regains 1d6 healing Hit Points.\n\nThe ghoul can regain Hit Points from a given body only once."

  - name: "Sneak Attack"
    desc: "  The ghoul stalker deals an extra 1d4 damage to creatures that have the [[Conditions/Off-Guard|Off-Guard]] condition."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghoul Stalker (BB)
creatures:
  - 1: Ghoul Stalker (BB)
```



The flesh-eating undead, known as ghouls, haunt sinister locations such as lonely graveyards and ruined crypts, making meals of corpses. Legends say that those captured by ghouls hear foul whispers that curse them into craving raw meat, eventually turning them into ghouls.
