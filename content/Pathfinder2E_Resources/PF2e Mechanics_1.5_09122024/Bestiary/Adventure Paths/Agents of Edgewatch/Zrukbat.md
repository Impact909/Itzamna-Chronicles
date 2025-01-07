---
title: "Zrukbat"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3GT034fY2pKSvla2" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Zrukbat"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Zrukbat"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[fey]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +9, Deception: +5, Stealth: +10"
abilityMods: [3, 4, 3, 1, -1, -1]
speed: 20 feet,  climb 20 feet,  fly 20 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +10, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30; __Immunities__  sleep; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 ()\n__Damage__  1d8 + 3 slashing"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+11 ()\n__Damage__  1d6 + 3 piercing"

  - name: "Dubious Shifting"
    desc: "`pf2:1` (concentrate,polymorph,primal) The zrukbat assumes the shape of any Small object or ornamentation, although the zrukbat's mimicked objects usually have unrealistic or suspicious quirks.\n\nThis doesn't change the zrukbat's size but can alter their coloration and visual appearance.\n\nThey have an automatic result of 23 on Deception checks and DCs to pass as the mimicked object."

  - name: "Go for the Eyes"
    desc: "`pf2:2`  The zrukbat flies up to its Speed and makes a claw Strike at the end of its move.\n\nIf the claw attack hits, the target must succeed on a DC 15 Fortitude check saving throw or be [[Conditions/Blinded|Blinded]] for 1 round (or blinded for 1 minute on a critical failure). If the Strike was a critical hit, the target's save result is one degree of success worse."
 
```

```encounter-table
name: Zrukbat
creatures:
  - 1: Zrukbat
```




