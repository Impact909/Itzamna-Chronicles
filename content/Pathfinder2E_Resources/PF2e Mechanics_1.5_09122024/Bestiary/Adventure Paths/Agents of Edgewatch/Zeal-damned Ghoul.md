---
title: "Zeal-damned Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OcbkzzTSwTNIEXXi" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Zeal-damned Ghoul"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Zeal-damned Ghoul"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +20, Deception: +18, Stealth: +22"
abilityMods: [4, 6, 3, 0, 3, 2]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +22, __Will__ +19"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 (finesse)\n__Damage__  2d6 + 8 piercing plus ghoul-fever,paralysis 1d6 spirit plus ghoul-fever,paralysis 1d6 void plus ghoul-fever,paralysis"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+22 (agile, finesse)\n__Damage__  2d4 + 8 slashing plus paralysis 1d6 void plus paralysis 1d6 spirit plus paralysis"

  - name: "Consume Flesh"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of an evil or chaotic creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 6d6 Hit Points. It can regain Hit Points from any given corpse only once."

  - name: "Ghoul Fever"
    desc: " (disease) **Saving Throw** DC 27 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a zeal-damned ghoul the next midnight."

  - name: "Paralysis"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 27 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Swift Leap"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Zeal-damned Ghoul
creatures:
  - 1: Zeal-damned Ghoul
```




