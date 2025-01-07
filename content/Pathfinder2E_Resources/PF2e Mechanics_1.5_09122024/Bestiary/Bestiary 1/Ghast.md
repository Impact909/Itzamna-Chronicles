---
title: "Ghast"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.RcKJw6ahXOYUk3sg" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Ghast"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Ghast"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +7, Stealth: +10, Survival: +8"
abilityMods: [3, 4, 2, 1, 2, 3]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +10, __Will__ +8"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghast) Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 16 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure).\n\nWhile within the aura, the creature takes a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse)\n__Damage__  1d6 + 5 piercing plus ghast-ghast-fever,ghast-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile, finesse)\n__Damage__  1d4 + 5 slashing plus ghast-paralysis"

  - name: "[[Creature Family Ability Glossary/(Ghast) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghast is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghast devours a chunk of the corpse and regains 3d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghast) Ghast Fever|Ghast Fever]]"
    desc: " (disease) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 3d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 3d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghast|Ghast]] the next midnight"

  - name: "[[Creature Family Ability Glossary/(Ghast) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a ghast's attack must succeed at a DC 16 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghast jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghast
creatures:
  - 1: Ghast
```



Ghasts-feral, foul-smelling, and constantly hungry-are the more powerful kin of ghouls. They are relentless in the pursuit of their prey.

* * *

Few creatures are more ubiquitous to sinister locations such as lonely graveyards and ruined crypts than the flesh-eating undead known as ghouls.
