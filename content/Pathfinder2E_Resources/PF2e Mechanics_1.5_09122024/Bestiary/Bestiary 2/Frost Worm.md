---
title: "Frost Worm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PX0Kq6hacQYQSTpq" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/cold
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Frost Worm"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Frost Worm"
level: "Creature 12"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[cold]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +25, Stealth: +20"
abilityMods: [7, 4, 6, -4, 4, 0]
speed: 25 feet,  burrow 10 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +22, __Will__ +20"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  cold; __Weaknesses__ fire 15"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Death Throes"
    desc: " (cold,primal) When a frost worm dies, it explodes in a 100-foot burst of searing cold blood. All creatures and objects in range take 10d8 cold damage (DC 29 Reflex check save)."

  - name: "Freezing Blood"
    desc: "`pf2:r` (cold) **Trigger** The frost worm takes piercing or slashing damage\n* * *\n\n**Effect** The frost worm's freezing blood sprays out on a random creature within 10 feet of the frost worm. That creature takes 7d6 cold damage (DC 29 Reflex check save)."

  - name: "Worm Chill"
    desc: " (aura,cold,primal) 5 feet. A creature that enters or begins its turn in the emanation takes 3d6 cold damage (DC 29 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+25 ()\n__Damage__  3d8 + 10 piercing 2d6 cold"

  - name: "Breath Weapon"
    desc: "`pf2:2` (cold,primal) The frost worm exhales a blast of frost, dealing 13d6 cold damage to creatures in a 50-foot cone (DC 32 Reflex check save).\n\nIt can't use Breath Weapon again for 1d4 rounds."

  - name: "Worm Trill"
    desc: "`pf2:1` (auditory,concentrate,mental,primal) The frost worm emits a hypnotic trill. Each non-frost worm creature within 100 feet must attempt a DC 32 Will check save. The effects of Worm Trill last for 1 round, but if the frost worm uses this ability again on subsequent rounds, it extends this duration by 1 round for any creature already affected.\n\n**Success** The creature is unaffected and is immune to Worm Trill for 24 hours.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] by the frost worm.\n\n**Critical Failure** As failure, but the fascinated condition doesn't end if the frost worm uses hostile actions against the creature."
 
```

```encounter-table
name: Frost Worm
creatures:
  - 1: Frost Worm
```



The frost worm's single round, red eye gleams prominently at the head of its monstrous mass, white as a winter snowfall. What appears to be a bifurcated lower jaw is actually two spiky parapodia that the worm uses to shovel food into its lamprey-like mouth. An adult frost worm measures 35 feet long and weighs 8,000 pounds.

A frost worm is an apex predator that uses camouflage, burrowing, and deceit to ambush its prey. When it attacks, a frost worm produces a distinctive, high-pitched trill. Though some survivors of frost worm attacks have compared it to a wailing lament, the trill has a captivating effect on nearby creatures, causing them to stop and listen even as the monstrous creature approaches.

The cold shed by a frost worm is as dangerous as its trill or its jaws, and while it is not fond of warmer climates, neither is it particularly hampered in such regions. A frost worm that somehow finds itself in temperate or even tropical environs causes the immediate area to chill and ice over with frost over time, creating seemingly impossible pockets of frozen terrain.
