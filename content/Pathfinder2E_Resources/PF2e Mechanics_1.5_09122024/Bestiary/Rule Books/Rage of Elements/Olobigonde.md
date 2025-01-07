---
title: "Olobigonde"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.P7UnAOtOpKPWmZ65" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Olobigonde"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Olobigonde"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[animal]]
trait_02: [[aquatic]]
trait_03: [[elemental]]
trait_04: [[water]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +10, Stealth: +9, Survival: +7"
abilityMods: [3, 1, 4, -4, 1, -5]
speed: 5 feet,  swim 30 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +10, __Ref__ +7, __Will__ +5"
hp: 38
health:
  - name: ""
  - name: HP
    desc: "38"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d8 + 3 piercing plus decomposing-toxin"

  - name: "Ambush"
    desc: "`pf2:r`  **Trigger** A target creature passes within 20 feet of the olobigonde's hiding place and has not detected the olobigonde\n* * *\n\n**Effect** The olobigonde lunges out of its hiding place, Swims directly toward the triggering creature, and makes a jaws Strike against it. The target creature is [[Conditions/Off-Guard|Off-Guard]] to this attack."

  - name: "Decomposing Toxin"
    desc: " (poison) A living creature struck by an olobigonde's jaws Strike must succeed at a DC 15 Fortitude check save or become [[Conditions/Enfeebled|Enfeebled 1]] and take 1d6 poison persistent damage (or [[Conditions/Enfeebled|Enfeebled 2]] with 2d6 poison persistent damage on a critical failure). The enfeebled condition ends when the persistent damage does. A creature currently affected by decomposing toxin doesn't need to save again."

  - name: "Reactive Grab"
    desc: "`pf2:r`  **Trigger** A creature within the olobigonde's reach leaves a square during a move action it's using\n\n**Requirements** The olobigonde doesn't have a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The olobigonde attempts to [[Actions/Grapple|Grapple]] the triggering creature with its jaws. On a success, the target also takes 3 piercing damage (doubled on a critical success)."
 
```

```encounter-table
name: Olobigonde
creatures:
  - 1: Olobigonde
```



Though the Plane of Water is mostly liquid, it does contain its share of solid material, whether in the form of free-floating aquatic plants, hunks of coral, or even detritus from lost underwater cities. Flotsam and jetsam collect across the plane, and olobigondes are just one of the many creatures that have evolved to live among and consume this detritus. These flat, round fish are covered in a moss-like skin that makes them exceptionally difficult to spot as they hug the sides of flotsam, feeding off the waste that drifts into their wide, open mouths.

While olobigondes are primarily detritivores, they've been known to lie in wait within a forest of kelp or against a mossy stone to ambush smaller creatures, such as water scamps or lone passing merfolk. The fish launch themselves from their hiding spot to take large bites out of their surprised prey, then grab the victim as it tries to flee. Despite their size and ungainly shape, olobigondes can move quickly in water, though their bursts of speed are usually short-lived. In addition to maintaining a firm hold on prey, olobigondes' mouths are filled with a unique toxin that weakens and decomposes living flesh. The hungry fish easily gulp down the resulting slurry.

Ancient olobigondes grow truly immense, and their outward appearance evolves. There seems to be no limit to their size. Their skin even separates into plates with deep channels where water can accumulate, giving them the appearance of an entire patch of detritus rather than one piece.

* * *

Alchemists who travel the planes have discovered how readily an olobigonde's toxin can decompose flesh, and some have discovered ways to incorporate it into their creations. An olobigonde's corpse yields approximately 1 gp worth of raw materials when harvested with a successful DC 16 Crafting check or Survival check (2 gp worth on a critical success). This material can be used only to craft alchemical bombs with the poison trait.
