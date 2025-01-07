---
title: "Cultist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EDs9gLD7JOoFbi4w" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Cultist"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Gamemastery Guide"
name: "Cultist"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Deception: +3, Intimidation: +3, Occultism: +3, Society: +4, Stealth: +6, Cult Lore (applies to cultist's own cult): +8"
abilityMods: [4, 3, 2, 1, -1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Gamemastery Guide_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +8, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Leather Armor|Cultist Garb]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+7 (agile, versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+6 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing"

  - name: "Fanatical Frenzy"
    desc: "`pf2:1`  **Requirements** The cultist has taken damage and is neither [[Conditions/Fatigued|Fatigued]] nor already in a frenzy\n* * *\n\n**Effect** The cultist flies into a frenzy that lasts 1 minute. While frenzied, the cultist gains a +1 status bonus to attack rolls and a +2 status bonus to damage rolls, and they take a -2 status penalty to AC. The cultist can't voluntarily stop their frenzy. After their frenzy, the cultist is [[Conditions/Fatigued|Fatigued]].\n\n[[Bestiary Effects/Effect_ Fanatical Frenzy|Effect: Fanatical Frenzy]]"
 
```

```encounter-table
name: Cultist
creatures:
  - 1: Cultist
```



Excessively zealous, a cultist finds exalted purpose in their sect. Never questioning their leader, they devote themselves to achieving their most perfect spiritual form.

* * *

Those initiated into the hidden truths and forbidden secrets of the world are forever transformed-or so they claim. To the cynical, a mystic is nothing more than a charlatan or zealot. Others profess to sense an aura around such luminaries and treat them with reverence, lest they offend some harbinger of unspeakable doom.
