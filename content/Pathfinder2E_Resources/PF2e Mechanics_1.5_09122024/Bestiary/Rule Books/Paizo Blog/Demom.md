---
title: "Demom"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wEvh5uqWvyoxJ1xx" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Demom"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Blog: April Fool&#x27;s Bestiary"
name: "Demom"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Truesight"
languages: "Chthonian, Common; telepathy 100 feet (knows what you&#x27;re thinking)"
skills:
  - name: "Skills"
    desc: "Diplomacy: +7, Intimidation: +8, Medicine: +10, Stealth: +8"
abilityMods: [3, 1, 0, 0, 4, 1]
speed: 30 feet
sourcebook: "_Pathfinder Blog: April Fool&#x27;s Bestiary_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +12, __Ref__ +9, __Will__ +7"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  disease,  mental,  sleep; __Resistances__ cold 10, electricity 10, fire 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "Maternal Aura"
    desc: " (aura) 50 feet. All creatures who have a tragic backstory in which they've lost their parents take a -4 penalty to all Will saves as they are suddenly overcome with feelings of maternal love."

  - name: "Shut It"
    desc: "`pf2:r`  **Trigger** A creature targets the demom with a hostile spell that has a verbal component.\n* * *\n\n**Effect** The demom says, \"Don't talk back to me!\" The caster must attempt a DC 18 Will check save; on a failure, it promptly shuts its mouth and stares at the ground contemplating how it doesn't deserve this."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hug"
    desc: "+10 (unholy)\n__Damage__  2d4 + 4 bludgeoning"

  - name: "**Ranged** `pf2:1` Stern Look"
    desc: "+10 (range increment 30 feet, unholy)\n__Damage__  1d10 + 3 fire"

  - name: "Ground Target"
    desc: "`pf2:3`  The demom narrows its eyes at a target and declares \"You're grounded!\" The target creature must attempt a DC 18 Will check save; on a failure, it must lay down its weapons, set up camp, and sit in its tent."

  - name: "There, There"
    desc: "`pf2:1` (emotion,healing,mental) **Requirements** The demom has a creature grabbed.\n* * *\n\n**Effect** The demom embraces the creature and pats its back soothingly as it whispers reassurances, restoring 10 Hit Points to the creature."
 
```

```encounter-table
name: Demom
creatures:
  - 1: Demom
```




