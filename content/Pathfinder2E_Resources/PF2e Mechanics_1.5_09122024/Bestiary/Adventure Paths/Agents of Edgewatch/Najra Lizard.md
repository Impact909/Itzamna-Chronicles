---
title: "Najra Lizard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.dMRsWPIVbMLoEnd9" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Najra Lizard"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Najra Lizard"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "tiny"
trait_01: [[chaotic]]
trait_02: [[dragon]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Deception: +10, Stealth: +12, Survival: +12"
abilityMods: [-1, 4, 2, -1, 3, 2]
speed: 30 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +12, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Shared Diversion"
    desc: "`pf2:r`  **Trigger** Another creature in the najra lizard's square succeeds at a Deception check to Create a Diversion\n* * *\n\n**Effect** The najra lizard automatically successfully [[Actions/Create a Diversion|Creates a Diversion]] against the same targets."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d6 piercing plus najra-lizard-venom"

  - name: "**Ranged** `pf2:1` Venomous Spit"
    desc: "+14 (agile, poison, range increment 20 feet)\n__Damage__  1d4 poison plus najra-lizard-venom"

  - name: "Najra Lizard Venom"
    desc: "  The creature is extremely thirsty and can't quench its thirst while poisoned\n\n**Saving Throw** DC 21 Fortitude check\n\n**Maximum Duration** 4 hours\n\n**Stage 1** 1d4 poison damage, [[Conditions/Fatigued|Fatigued]], and 1d4 damage that can't be recovered until the creature quenches its thirst (1 round)\n\n**Stage 2** as stage 1 (1 hour)"

  - name: "Najra Swarm Attack"
    desc: "  The najra lizard's melee Strikes deal 1d6 precision damage to creatures sharing a square with more than one najra lizard."
 
```

```encounter-table
name: Najra Lizard
creatures:
  - 1: Najra Lizard
```




