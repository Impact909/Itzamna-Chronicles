---
title: "Profane Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.H9uRyIv6N0iKFx9s" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Profane Ghoul"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Shadows at Sundown"
name: "Profane Ghoul"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ghoul]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +17, Religion: +19, Stealth: +20"
abilityMods: [3, 6, 5, 3, 5, 5]
speed: 30 feet,  burrow 10 feet
sourcebook: "_Pathfinder Adventure: Shadows at Sundown_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +17, __Ref__ +22, __Will__ +19"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 (finesse)\n__Damage__  2d10 + 7 piercing plus ghoul-ghoul-fever,profane-paralysis 2d6 void plus ghoul-ghoul-fever,profane-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile, finesse)\n__Damage__  2d6 + 7 slashing plus profane-paralysis 2d6 void plus profane-paralysis"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 29 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "Profane Paralysis"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by the profane ghoul's attack must attempt a DC 29 Fortitude check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Slowed|Slowed 1]].\n\n**Failure** The creature is [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Profane Whispers"
    desc: "`pf2:2` (auditory,mental,occult) The ghoul whispers profane secrets of undeath. Living creatures within 10 feet of the ghoul take 2d8 persistent mental damage. Those with ghoul fever must also succeed at a DC 29 Will check save or have the disease advance one step. The profane ghoul can't use Profane Whispers again for 24 hours."

  - name: "Scuttle"
    desc: "`pf2:1` (move) The profane ghoul crawls on all fours, moving up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Profane Ghoul
creatures:
  - 1: Profane Ghoul
```


Variant ghoul


