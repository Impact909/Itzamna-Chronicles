---
title: "Cacaodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TMiByS8VMlz4GURp" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Cacaodaemon"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog: April Fool&#x27;s Bestiary"
name: "Cacaodaemon"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 2
perception:
  - name: "Perception"
    desc: "+2; "
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Deception: +7, Nature: +3, Religion: +4, Stealth: +5"
abilityMods: [3, 1, 4, -2, 0, 1]
speed: 5 feet,  fly 40 feet
sourcebook: "_Pathfinder Blog: April Fool&#x27;s Bestiary_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +10, __Ref__ +7, __Will__ +4"
hp: 22
health:
  - name: ""
  - name: HP
    desc: "22; __Immunities__  death effects; __Resistances__ bludgeoning 2"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Aromatic"
    desc: "  When a cacaodaemon is reduced to half its HP, the ruptures to its rind exude a fragrant tropical scent. Creatures within 10 feet of the cacaodaemon take a -1 circumstance penalty to Will saving throws until the cacaodaemon dies or is healed above half its HP."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Nib Teeth"
    desc: "+9 (unholy)\n__Damage__  1d6 + 3 piercing plus bitter-heart"

  - name: "Bitter Heart"
    desc: " (poison) The dissonance between the cacaodaemon's sweet scent and bitter inside drains the victim's spirit\n\n**Saving Throw** DC 17 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d8 mental damage and [[Conditions/Off-Guard|Off-Guard]] (1 round).\n\n**Stage 2** 1d8 mental damage and [[Conditions/Stupefied|Stupefied 1]] (1 round)\n\n**Stage 3** 1d12 mental damage and [[Conditions/Stupefied|Stupefied 2]] (1 round)"
 
```

```encounter-table
name: Cacaodaemon
creatures:
  - 1: Cacaodaemon
```




